# Emoji

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus mi erat, sodales sed cursus at, condimentum at neque. Vivamus sollicitudin felis nec commodo semper.

:::BlockQuote
⚠️ **Warning:** Do not push the big red button.
:::

:::BlockQuote
📝 **Note:** Sunrises are beautiful.
:::

:::BlockQuote
💡 **Tip:** Remember to appreciate the little things in life.
:::

- a test

:::::WorkflowBlock
:::WorkflowBlockItem
To add the Google Analytics tracking code to your documentation portal, you’ll need a piece of code known as the “**Global Site Tag**.”

You can find this in your Google Analytics admin dashboard. Locate the tracking code under **Admin -> Data Streams -> Web stream details**.
:::

:::WorkflowBlockItem
Copy the global site tag below into the **Custom JavaScript** field under **Space Settings -> Custom Code**.

![](https://archbee-image-uploads.s3.amazonaws.com/bNBm7nPJgXjbjLyfbHNh2/rwPtIGtKjQqfSmJ5MWIPU_guides-customjs-light.png "Globat site tag code")
:::

:::WorkflowBlockItem
Make sure you replace the `insert measurement ID` with your own ID.

```javascript
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-80B7MQZ06B"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', '{insert measurment ID}');
</script>
```
:::

::::WorkflowBlockItem
After the code is added, click **Save** and publish to production.

:::hint{type="warning"}
For security reasons, custom code is only included on a custom domain.
:::
::::
:::::

