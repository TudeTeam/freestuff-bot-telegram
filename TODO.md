
# TODO:

## Database

- [ ] Update to the latest database changes.
  - [x] Update the defined structures.
  - [ ] Fix the synchronization tasks.
- [x] Define the structure for outgoing Telegram announcements.
- [x] Update the announcements' system to use redis instead of
MongoDB for storing the progress.
- [x] Collect analytics for the Telegram announcements.
  - [x] Define the redis structure for the analytics.
  - [x] Put the result analytics into MongoDB once published.
- [ ] Make the watcher filter for `accepted` games instead of `published`.
- [ ] Implement the chat id migration thing for groups and supergroups.

## Settings Menu

- [x] Implement the minimum price option.
- [x] Add a close menu button.
- [ ] Create a sub-menu for filtering by store.
  - [ ] Add buttons to enable or disable all.
- [ ] Create `/channel_menu` for configuring the bot on a channel.

## Miscellaneous

- [ ] Improve the `/free` command with inline buttons.
- [ ] Documenting the bot for users:
  - [ ] Write the about text of the bot.
  - [ ] Write the description of the bot.
  - [ ] Write the `/help` command of the bot.
  - [ ] Write the help option in the configuration menu.
  - [ ] Write a better welcoming message.
  - [ ] Write a welcoming message for groups.
- [ ] Implement the `support bot` button.

## Maintenance

- [ ] Use SLF4J framework for logging.
- [ ] Create a files logging system if there's no one.
  - [ ] Switch to a new log file at 00:00 each day.
  - [ ] Compress the old log files.
  - [ ] Archive each month in a `.zip`.
- [ ] Use Prometheus for collecting metrics.
  - [ ] Setup the scraper.
  - [ ] Setup the Grafana dashboard.
  - [ ] Setup Grafana alerts.
