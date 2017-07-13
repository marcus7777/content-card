# content-card
This card is designed to have lots of users with a single expert, all users can change their card. Only Changes by the experts are visible to all, users can share the changes with the expert.

Data layout

```
Cards/
  [cardID]/
    title/
    article/
    bigImage/
    desc/
    image/
      [time][uid]/
        time:[time]
        user:[user]
        value:[value]
    readable/
    writable/
      all: true/false
      [uid]: true/false
