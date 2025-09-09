# l2-data-notifications

This repository contains a single GitHub Actions workflow that compares the contents of the L2 Data SFTP server to the contents of our Google Drive folder, and posts a message on the `#cidr-data` channel on the Stanford Slack Grid if there are new files we've not downloaded and archived yet.
