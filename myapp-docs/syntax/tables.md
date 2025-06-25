# Tables

<table isTableHeaderOn="true" selectedColumns="" selectedRows="" selectedTable="false" columnWidths="121">
  <tr>
    <td selected="false" align="left">
      <p>Date</p>
    </td>
    <td selected="false" align="left">
      <p>Changes</p>
    </td>
  </tr>
  <tr>
    <td selected="false" align="left">
      <p>April, 2025</p>
    </td>
    <td selected="false" align="left">
      <p>New methods were added:</p>
      <ul>
      <li>JazzCash (Pakistan) - GAPI payment method</li>
      <li>Interac (Canada) - MAPI payout method</li>
      </ul>
      <p><img src="https://archbee-image-uploads-qa.s3.amazonaws.com/BbT7KQqqvz3LSYn2rwmao/okImeFmr_F9thLy7w2hcj_image.png" alt=""></p>
    </td>
  </tr>
  <tr>
    <td selected="false" align="left">
      <p>March, 2025</p>
    </td>
    <td selected="false" align="left">
      <p>API callback messages are now sent with the status <code>actionRequired</code> in case of additional processing/checking period by the bank. For the status <code>actionRequired</code> are now sent action.type and action.details as well.</p>
      <p>The generating and checking message token process has changed due to a new structure of API callback message. New methods were added:</p>
      <ul>
      <li>Netbanking (India) - MAPI payout</li>
      <li>PayID - MAPI payout / GAPI payout</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td selected="false" align="left">
      <p>February, 2025</p>
    </td>
    <td selected="false" align="left">
      <p>For the <strong>applepay</strong> payment method, the following parameters are now <strong>required</strong>: <em>session.order.customer.personsData.country</em></p>
      <p><em>session.order.customer.personsData.firstName</em></p>
      <p><em>session.order.customer.personsData.lastName</em></p>
      <p>in the <a href="">Start Payment Session</a> method. - <em>customer.address.country</em> in the <a href="">Create Payment</a> method.</p>
    </td>
  </tr>
  <tr>
    <td selected="false" align="left">
      <p>January, 2025</p>
    </td>
    <td selected="false" align="left">
      <p>: the max length of the <em>sessionContext.browserParameters.accept</em> parameter has been changed from 100 to 2000 symbols.</p>
    </td>
  </tr>
  <tr>
    <td selected="false" align="left">
      <p>January, 2025</p>
    </td>
    <td selected="false" align="left">
      <ol>
      <li><em><strong>Upi</strong></em> payment method: the max length of the first name and last name parameters in the <a href="">Start Payment Session</a> and <a href="">Create Payment</a> methods is now <strong>40</strong>.</li>
      <li>Every <a href="">Get Payment Status</a> response now includes the <em>session.payment.amount</em> parameter, regardless of the current payment status.</li>
      <li>New payment/payout status, <code>cancelledByCustomer</code> , has been added to <a href="">Operation statuses</a>. The status means that a customer declined the payment or payout attempt and returned to the merchant page.</li>
      </ol>
    </td>
  </tr>
</table>

## second table

<table isTableHeaderOn="true" selectedColumns="" selectedRows="" selectedTable="false">
  <tr>
    <td selected="false" align="left">
      <p>a</p>
    </td>
    <td selected="false" align="left">
      <p>b</p>
    </td>
    <td selected="false" align="left">
      <p>c</p>
    </td>
  </tr>
  <tr>
    <td selected="false" align="left">
      <p>a</p>
    </td>
    <td selected="false" align="left">
      <ol>
      <li>amic</li>
      <li>lul
      <img src="https://archbee-image-uploads-qa.s3.amazonaws.com/BbT7KQqqvz3LSYn2rwmao/NDq_K8d455NUwWKEwKiSK_woocommercemanage.png" alt=""></li>
      </ol>
    </td>
    <td selected="false" align="left">
    </td>
  </tr>
  <tr>
    <td selected="false" align="left">
    </td>
    <td selected="false" align="left">
      <ul>
      <li><a href="">Lists 1</a></li>
      <li><a href="./../directives/link-arrays.md">Link arrays</a></li>
      </ul>
    </td>
    <td selected="false" align="left">
    </td>
  </tr>
  <tr>
    <td selected="false" align="left">
    </td>
    <td selected="false" align="left">
      <ul>
      <li>a</li>
      <li>b</li>
      </ul>
    </td>
    <td selected="false" align="left">
    </td>
  </tr>
</table>

