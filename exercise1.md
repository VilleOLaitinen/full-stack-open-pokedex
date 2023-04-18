Let's assume we are using Python in this exercise.

For the first point of discussion, with some googling help, Flake8 seems to be a decent choise
for our linting needs, while testing can be done using pytest and tox. Setuptools for building purposes.

On the second point, alternatives to GitHub Actions and Jenkins I could find include BitBucket Pipelines and Gitlab CI
solutions as comparable alternative to GitHub, TracisCI, Semaphore.
That's naming a few that are easy to come accross with Google, but I assume there are countless
options available.

Regarding the third point, of course there is not too much context given on what the project is like so it's bit of guesswork.
The information needed to make a calculated choise would include some of the topics mentioned in the material, such as possible need
for secrecy for the project, possibly how experienced or confident in general our team is using our own hosted setups and possible
resources (hardware including possible backups?) needed versus likely simpler and faster cloud based solution.

Considering the team is only 6 people the project likely isn't insanely complex, cloud-based option is more likely candidate if we have no
special requirements?

Of course, answering these questions will become a lot more easier once I actually get some first hand experience on the different options in
future projects!
