# Active Storage Image Attachment Demo

Starting App: We begin with the app produced in the [Demos-n-Deets Resource Ownership Demo](https://rails-demos-n-deets-2022.herokuapp.com/demos/resource-ownership). This app is for creating quizzes made up of multiple-choice questions and includes user authentication and authorization. The code for this app can be found here: <https://github.com/human-se/rails-demos-n-deets-2021-app/tree/demo-resource-ownership>

Demo Goal: The goal of this demo is to enable image attachments for questions. Specifically, a user who is creating or updating a question should be able to attach a figure image that is displayed as part of the question.

Demo Video: <https://www.youtube.com/watch?v=EmklBPiRlpQ>

Demo Code: The code resulting from the demo video can be viewed in this commit: <https://github.com/human-se/demo-active-storage-image-attach-2022-04-20/commit/33fc1adffc271072960f019be10aa51736e97c21>

## Fixing the File Field Widget

After completing the original demo, it was noted that the widget for choosing the image file (`file_field`) wasn't working correctly. In particular, after a user selects an image file, it doesn't display the name of the selected file like it's supposed to. It turns out that this is a known bug with the `bootstrap_form_with` widget (issue: <https://github.com/bootstrap-ruby/bootstrap_form/issues/528>). Fortunately, the issue discussion contained a workaround to fix the problem, which I demonstrated in the following video.

Demo Video: <https://youtu.be/454QuJ8fmIw>

Demo Code: The code resulting from the demo video can be viewed in this commit: <https://github.com/human-se/demo-active-storage-image-attach-2022-04-20/commit/07557ba4dd3e77ef4e01df2f66e0edee9ec4ce2f>
