Form tag example

```html
<form form="https://app.modaltrans.com/roster/web_request_quotes" method="post">
```

Add this script tag to the end of the body (required)
```html
<script src="http://app.modaltrans.com/roster/web_requests.js"></script>
```



Your custom account token (required)

```html
<input type="hidden" id="patron_token" name="web_request_quote[patron_token]" value="{{YOUR_ACCOUNT_TOKEN}}" required>
```

User Name (required)

```html
<label for="name">Name</label>
<input type="text" id="name" name="web_request_quote[name]" required>
```

Company Name (required)

```html
<label for="company_name">Company Name</label>
<input type="text" id="company_name" name="web_request_quote[company_name]" required>
```

Tax No

```html
<label for="tax_no">Tax No</label>
<input type="text" id="tax_no" name="web_request_quote[tax_no]">
```

Email (required)

```html
<label for="email">Email</label>
<input type="text" id="email" name="web_request_quote[email]" required>
```

Phone

```html
<label for="phone">Phone</label>
<input type="text" id="phone" name="web_request_quote[phone]">
```

Trans Mode

```html
<label for="trans_mode">Transport Mode</label>
<select id="trans_mode" name="web_request_quote[datas][trans_mode]" required>
  <option value="road">Road</option>
  <option value="sea">Sea</option>
  <option value="air">Air</option>
  <option value="rail">Rail</option>
</select>
```

Shipment Type (required)

```html
<label for="full_partial">Shipment Type</label>
<select id="full_partial" name="web_request_quote[datas][full_partial]" required>
  <option value="partial">Partial</option>
  <option value="full">Full</option>
</select>
```

Total Package

```html
<label for="total_package">Total Package</label>
<input type="number" id="total_package" name="web_request_quote[datas][total_package]">
```

Gross Weight

```html
<label for="gross_weight">Gross Weight</label>
<input type="number" id="gross_weight" name="web_request_quote[datas][gross_weight]">
```

Total Volume

```html
<label for="total_volume">Total Volume</label>
<input type="number" id="total_volume" name="web_request_quote[datas][total_volume]">
```

Lead Class (required)

```html
<label for="lead_class">Lead Class</label>
<select id="lead_class" name="web_request_quote[datas][lead_class]" required>
    <option value="standard">Standard</option>
    <option value="adr">ADR</option>
    <option value="perishable">Perishable</option>
    <option value="pharma">Pharma</option>
    <option value="animal">Animal</option>
    <option value="funeral">Funeral</option>
    <option value="other_special_cargo">Other Special Cargo</option>
    <option value="bulk">Bulk</option>
</select>
```

Origin Address (required)

```html
<label for="origin_address">Origin Address</label>
<input type="text" id="origin_address" name="web_request_quote[datas][origin_address]" required>
```

Origin Postcode

```html
<label for="origin_postcode">Origin Postcode</label>
<input type="text" id="origin_postcode" name="web_request_quote[datas][origin_postcode]">
```

Origin Country (required)

```html
<label for="origin_country_id">Origin Country</label>
<select id="origin_country_id" name="web_request_quote[datas][origin_country_id]" mdl-web-request="countries_option" required>
  <option value=""></option>
</select>
```

```
mdl-web-request="countries_option" # Takes countries
```

Destination Address (required)

```html
<label for="destination_address">Destination Address</label>
<input type="text" id="destination_address" name="web_request_quote[datas][destination_address]" required>
```

Destination Postcode

```html
<label for="destination_postcode">Destination Postcode</label>
<input type="text" id="destination_postcode" name="web_request_quote[datas][destination_postcode]">
```

Destination Country (required)

```html
<label for="destination_country_id">Destination Country</label>
<select id="destination_country_id" name="web_request_quote[datas][destination_country_id]" mdl-web-request="countries_option" required>
  <option value=""></option>
</select>
```

```
mdl-web-request="countries_option" # Takes countries
```

Special Instructions
```html
<label for="special_instructions">Special Instructions</label>
<textarea id="special_instructions" name="web_request_quote[datas][special_instructions]"></textarea>
```

Customer Reference
```html
<label for="customer_ref">Customer Reference</label>
<input type="text" id="customer_ref" name="web_request_quote[datas][customer_ref]">
```

Notes
```html
<label for="notes">Notes</label>
<textarea id="notes" name="web_request_quote[datas][notes]"></textarea>
```
