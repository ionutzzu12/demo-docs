---
title: Emoji
docTags: 
createdAt: Thu Oct 01 2026 11:01:44 GMT+0300 (Eastern European Summer Time)
---

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

![](https://archbee-image-uploads-qa.s3.amazonaws.com/yzXkkCTORWlcwRG_AVHKZ/2gu6GJ8A-lBq_D0ZOx8Vx-20261001-110248.png "Globat site tag code")
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

<table isTableHeaderOn="true">
  <tr>
    <td>
      <h1>dadsad</h1>
    </td>
    <td>
      <p>da</p>
    </td>
    <td>
      <h2>ds</h2>
    </td>
  </tr>
  <tr>
    <td>
      <p>1</p>
    </td>
    <td>
      <p>2</p>
    </td>
    <td>
      <p>3</p>
    </td>
  </tr>
  <tr>
    <td>
      <p>dadadadads</p>
      <ul>
      <li>dadadadsa dadadsadadsdsa</li>
      </ul>
    </td>
    <td>
      <p><strong>adadad</strong></p>
    </td>
  </tr>
  <tr>
    <td>
      <p><em>ffrf</em></p>
    </td>
    <td>
      <ul>
      <li>dasdad</li>
      </ul>
    </td>
    <td>
    </td>
  </tr>
</table>

Stress test line from branch p (safe to delete)
