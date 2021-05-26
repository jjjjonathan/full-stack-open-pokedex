For this assignment, I'm imagining I'm working with a team of six other people on a simple Python application that will help users log their to-do list. It will be compact and not overburdened with unnecessary features.

A tool that might be used for linting in this case would be flake8, which checks the code's conformity to Python standards. For testing, using Python's built-in features for unit testing might work, or else the pytest library is another common solution. The build step probably won't be necessary for this application, because Python is an interpreted language.

One alternative to Jenkins would be Buildkite. Buildkite is described on their website as a hybrid SaaS platform designed for enterprise scale. Another option is CircleCI. Like Jenkins, it's compatible with both on premise & in cloud hosting. TeamCity is another potential choice which does not have a cloud option available; it's only for creating your own server. Bamboo and Gitlab are two further choices that seem to be less expensive to get started than some of the other options.

This particular setup would probably be better suited to a cloud-based environment, primarily because of its small size. The small team will already be familiar with Github, and the relative simplicity of the application code probably won't create any use cases that Github actions won't be able to handle.
