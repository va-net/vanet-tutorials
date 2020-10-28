# Slack/Discord Notifications for Flare

One of the most popular plugins for Flare is the Notifications plugin. This plugin adds the ability to send Slack/Discord messages whenever certain things happen. This is an official plugin.

## Post-Installation

After installing the Notifications plugin, a **Notifications** page will be added the **Plugins** menu. This page is where you can add your webhooks. Note that there are two webhooks required, the Public one and the Private one. See below for what goes to each webhook.

| Event         | Webhook |
| ------------- | ------- |
| PIREP Filed   | Public  |
| News Added    | Public  |
| User Applied  | Private |
| Flare Updated | Private |

## Creating Webhooks

### Discord

Creating webhooks in Discord is easy. See [this article](https://support.discord.com/hc/en-us/articles/228383668) for how to set up Discord Webhooks. Remember, you'll need one webhook going to a public feed channel and a separate one going to your internal staff channel. Also, if you don't mind, we recommend setting the webhook icon [as the VANet Logo](https://vanet.app/img/logo.png).

Once you've got your webhooks, paste the public one in the **Public Channel Webhook** field, the private one in the **Private Channel Webhook**, select your **Platform** as Discord, and away you go. Updates will now be sent to each channel as needed. Maybe add a news item to test it out!

### Slack

Adding webhooks in Slack is a bit more complex, but still doable. Follow [this tutorial](https://api.slack.com/messaging/webhooks) up until the end of step 3. To make a private webhook, then repeat step 3 to make your public webhook. Now, paste each link into their respective fields, set your **Platform** to Slack, click save and you're good to go. Why not File a PIREP to test it out?