# Digivizer - React.js tech test
## Intro

Thanks for your interest in Digivizer! Our React.js technical interview process involves candidates doing an at-home project to test your React.js knowledge and problem solving abilities, while also giving you a chance to write code in a way that you find comfortable.

This test should take about **1 hour**. If you take less time, no problem! If you take more time, that's cool too but don't spend more than 2 hours working on this. Using Google/StackOverflow/whatever for help is allowed, but ultimately you should write and be able to justify every piece of the code being submitted.

Your solution should be shared on a public Github or Bitbucket repo showing all commit history.

## Task

Given [ this JSON dataset](./public/earned.json) render a set of social media posts. Using React.js, fetch the JSON data, and render out the `username`, `date`, `image_url`, `post`, along with `likes_count`, `comments_count` and `engagement` (which is calculated as the sum of `likes_count` and `comments_count`) as a table. The `image_url` should be rendered as a thumbnail.

| Author | Date | Post | Post Image | Likes Count | Comments Count | Total Engagement↓|
|--------|------|------|------------|-------------|----------------|------------------|
| tonyhollingsworth | 18th July 2021 | Great coffee where I grew up in South Coogee... | 🖼️ | 35 | 1 | 36 |
| bigyaho | 13th July 2021 | June was another record month for @CardlyNet. | | 13 | 0 | 13 |

So that our team can determine the overall performance of this channel, please ensure that the data is shown in order of engagement, descending.

## Requirements
- Use ReactJS (`create-react-app` encouraged)
- You can use either Hooks or standard react, but in either case the correct use of state and props is required, as well as correct component abstraction (ie knowing when to make something a subcomponent)
- You should attempt to make your rendered table as close to the example as possible, deriving the calculations necessary to show the engagement
- This is not a UX test, focus on the functionality


## Bonus points
- Make the table columns sortable, feel free to use a table / UI library
- Cover your code with tests you think are most appropriate
