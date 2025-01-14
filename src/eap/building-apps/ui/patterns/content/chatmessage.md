---
tags: 
summary: Chat Message displays conversation posts in notifications or chat screens.
locale: en-us
guid: e2779043-5437-4ee5-aed8-03b1a2f1ff85
app_type: mobile apps, reactive web apps
platform-version: odc
---

# Chat Message

You can use the Chat Message UI Pattern to display conversational posts in notifications or chat screens. It can be used to display content such as photos, text, images, delivery times, and statuses.

![](<images/chatmessage-3.png>)

**How to use the Chat Message UI Pattern**

1. In ODC Studio, in the Toolbox, search for `Chat Message`.
  
    The Chat Message widget is displayed.

    ![](<images/chatmessage-1-ss.png>)

1. From the Toolbox, drag the Chat Message widget into the Main Content area of your application's screen.

    ![](<images/chatmessage-2-ss.png>)

    By default, the Chat Message widget contains Image and Content placeholders.

1. Add the relevant content to the placeholders.

    In this example, we add the user avatar to the Image placeholder and text to the Content placeholder. 

    ![](<images/chatmessage-4-ss.png>)

    Alternatively, you can use, for example, a List to display a Chat Message for each message record on an entity. You can also use a form to allow users enter their messages. By using the relevant expressions and logic, once the user sends their message, refresh the list of messages so it appears as a conversational post.

1. You can customize the Chat Message's look and feel by setting the (optional) properties on the **Properties** tab.

    ![](<images/chatmessage-5-ss.png>)

After following these steps and publishing the app, you can test the pattern in your app.

## Properties

| Property                                           | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| DisplayOnRight (Boolean): Optional                 | If True, the pattern is right aligned. If False, the pattern is left aligned. This is the default value.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Time (Time): Optional                              | Message timestamp.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| MessageStatus (MessageStatus Identifier): Optional | The status of the current message, for example, sent recieved, read, and hidden.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ExtendedClass (Text): Optional                     | Adds custom style classes to the Pattern. You define your custom style classes in your application using CSS. <p>Examples <ul><li>Blank - No custom styles are added (default value).</li><li>"myclass" - Adds the ``myclass`` style to the UI styles being applied.</li><li>"myclass1 myclass2" - Adds the ``myclass1`` and ``myclass2`` styles to the UI styles being applied.</li></ul></p>You can also use the classes available on the OutSystems UI. |
