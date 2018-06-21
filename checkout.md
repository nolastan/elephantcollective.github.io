---
layout: default
title: The Elephant Collective Checkout
---

<script src="https://js.chargebee.com/v2/chargebee.js"
        data-cb-site="elephantcollective"> </script>

<div class="input-field col s12">
  <select>
    <option value="" disabled selected>Choose your billing period</option>
    <option value="the-herd">Monthly  $25</option>
    <option value="the-herd-monthly">6 Months $125</option>
    <option value="the-herd">Yearly   $200</option>
  </select>
  <label>Period</label>
  <select>
    <option value="" disabled selected>Would you like to make an additional donation?</option>
    <option value="5">5</option>
    <option value="10">6 Months $125</option>
    <option value="15">Yearly   $200</option>
  </select>
  <label>Donation</label>
</div>

<a class="btn waves-effect waves-light pink"
   href="javascript:void(0)"
   data-cb-type="checkout"
   data-cb-plan-id="the-herd">
  Subscribe
</a>

<a href="javascript:void(0)"
   data-cb-type="portal">
  Manage Account
</a>