# Visualizing voting in the Belgian federal parliament (chamber)

We believe that in a democracy, it should be transparent and easily understandable what politicians, who represent the people, voted for.

This project aims to visualize the voting behavior of the politicians in the Belgian federal parliament (Chamber) in 2024.

## First prototype: textual summary of recent voting behavior

As a first visualization, the fetched voting behavior is summarized as text in https://github.com/transparentdemocracy/voting-data/tree/main/data/output, per plenary session in the Chamber.

## Next : a voting quiz?

One of the goals we are aiming at, is a voting quiz that helps you decide which political party and individual politicians represented best your own preferences.

This as opposed to most voting quizes in the Belgian media currently, except for De Morgen / HLN, and with the added benefit of being able to understand which individual politicians are most aligned with your preferences.

Contrary to voting quizes in the media, we want to keep voting behavior transparent also after the upcoming elections.

On longer term, we want to expand to visualizing voting behavior in the federal senate, the Flemish and other Belgian governments and the European government.


## Developer guide

This project currectly consists out of three code repositories

+ voting-data: Responsible for parsing the official documents, extracting all the data in JSON format. Written in python.
+ backend : A backend responsible for serving the data in several forms, making it searchable, navigatable, through a REST api. Written in Java.
+ website: The frontend that visualizes the information obtained from the backend. Written in Angular.

![Overview](./profile/img/overview.jpg)


## Convinced of this project's potential?

We are looking for software developers, designers, marketeers, translators,...

To get an idea of the **ideas we have planned on a high-level**, have a look at [our board of planned ideas](https://github.com/orgs/transparentdemocracy/projects/1/views/1).

Of course, **concrete implementation ideas, details and discussions related to this voting-data project**, are
tracked as issues in the individual repositories of this organization, like [here](https://github.com/transparentdemocracy/voting-data/issues).

If you are interested to work on a certain feature, let us know via the above links.
When you start to contribute, check the readme.md and contribute.md of the project you will contribute to!

If you want to bring ideas too, welcome! 
- You can create Github issues if they are relevant to an already existing repository in this organization.
- We have a public [discussion channel](https://github.com/orgs/transparentdemocracy/discussions) here on Github and a private discussion channel on Slack.
