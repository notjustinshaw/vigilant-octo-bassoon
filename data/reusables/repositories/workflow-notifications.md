If you enable email or web notifications for {% data variables.product.prodname_actions %}, you'll receive a notification when any workflow runs that you've triggered have completed. The notification will include the workflow run's status (including successful, failed, neutral, and canceled runs). You can also choose to receive a notification only when a workflow run has failed.

Notifications for scheduled workflows are sent to the user who initially created the workflow. If a different user updates the cron syntax in the workflow file, subsequent notifications will be sent to that user instead.

You can also see the status of workflow runs on a repository's Actions tab. For more information, see "[Managing a workflow run](/actions/automating-your-workflow-with-github-actions/managing-a-workflow-run)."
