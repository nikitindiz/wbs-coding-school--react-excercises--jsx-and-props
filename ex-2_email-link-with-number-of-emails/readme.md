![email-notification-v1](email-notification-v1.jpeg "email-notification-v1")
# \<EmailLink />

Create `EmailLink` component, that renders `<a>` tag with given `href` with email icon. In addition, it should display number of emails defined via `numberOfUnread` prop.

You can use [material design icons svg files](https://material.io/resources/icons/?search=email&icon=notifications_none&style=baseline).

## Expected use cases:

*Should render email icon with 10 in a circle:*
```
<EmailLink
    href="/?page=emails"
    numberOfUnread={10}
/>
```

*Should render just email icon:*
```
<EmailLink
    href="/?page=emails"
    numberOfUnread={0}
/>

<EmailLink
    href="/?page=emails"
/>
```

# Examples
![email-notification-v2](email-notification-v2.jpg "email-notification-v2")
![email-notification-v3](email-notification-v3.jpg "email-notification-v3")
