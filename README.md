# better-likes
Overview: To create a system for more efficient search and filter of ideas, rather than popularity, to explore and tell stories from data.

## write
- prompts a question
- response is given a 5 x 5 grid with up to 4 axis of responses
- values are registered as a sigmoid function incrementing 1, 0 and -1 for each axis
- stores value for those tags under the associated title in question

## read
- search by tag to see the associated prompts, filtered by the value
- create rule sets to return ordered and unordered lists of prompts based on the values for that tag
BONUS:
- visualize this data as a force directed graph and explore prompts
- categories for prompts (that aren't related to the tags being voted on for association, but rather for finding the actual prompt)
