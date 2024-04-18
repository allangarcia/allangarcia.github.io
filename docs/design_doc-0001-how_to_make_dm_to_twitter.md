### How to make DM to Twitter/X

#### Requirement

- Being able to send DM directly from a href link

#### How was implemented

1. Search for user_id in the source code of you logged page
2. Using user_id=1652324321824579587
3. Change the "Contact me" buttom link href to https://twitter.com/messages/compose?recipient_id=1652324321824579587

```html
<a
  href="https://twitter.com/messages/compose?recipient_id=3805104374&text=Hello%20world"
  class="twitter-dm-button"
  data-screen-name="@furni"
>
  Message @furni</a
>
```

Reference:
https://developer.twitter.com/en/docs/twitter-for-websites/direct-message-button

#### What is a success?

- The button "Contact me", instead of using the carrd proprietary cgi change to DM directly to Twitter/X
