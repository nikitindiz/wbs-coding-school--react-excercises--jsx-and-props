![](bell.png "email-notification-v1")

# \<NotificationLink />

Create `NotificationLink` component, that renders `<a>` tag with given `href` with bell icon.

It should render `notifications_none-24px.svg` when `haveUnread` jsx attribute (prop) value is `false`. And `notifications-24px.svg` when it's `true`.

## Expected use cases:

*Should render `notifications-24px.svg`:*
```
<NotificationLink
    href="/?page=notifications"
    haveUnread={true}
/>
```

*Should render `notifications_none-24px.svg`:*
```
<NotificationLink
    href="/?page=notifications"
    haveUnread={false}
/>

<NotificationLink
    href="/?page=notifications"
/>
```
