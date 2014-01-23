AlfredSlackSearch
=================

This is an [Alfred.app](http://www.alfredapp.com/) workflow that searches your organization's [Slack](https://slack.com/) chat history. Just type `slack` followed by your query to search all of your channels. Pressing `return` on a result will open the result in your web browser.

![Preview screenshot](https://raw.github.com/tylerhall/AlfredSlackSearch/master/preview.png)

## Setup

[Download the Alfred Workflow](https://github.com/tylerhall/AlfredSlackSearch/blob/master/SearchSlack.alfredworkflow?raw=true). Double-click to install.

You'll need to edit the workflow and add your own Slack authentication token. You can [generate a token here](https://api.slack.com/).

1. Open Alfred's Preferences.
2. Choose the "Workflows" tab.
3. Select "Search Slack".
4. Double click the first workflow item named "slack script filter"
5. Scroll down through the code and insert your authentication token into the line that looks like this...

    `$token = 'xoxp-16253-23648123-2379487234-239876478';`

6. Click "Save".
