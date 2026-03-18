
# Adres

<p>Adres van een brouwerij</p>

<table>
<tbody>
<tr><th>$id</th><td>https://schemas.don.apps.digilab.network/demo/demo/adres</td></tr>
<tr><th>$schema</th><td>https://json-schema.org/draft/2020-12/schema</td></tr>
</tbody>
</table>

## Properties

<table class="jssd-properties-table"><thead><tr><th colspan="2">Name</th><th>Type</th></tr></thead><tbody><tr><td colspan="2"><a href="#straat">straat</a></td><td>String</td></tr><tr><td colspan="2"><a href="#huisnummer">huisnummer</a></td><td>Number</td></tr><tr><td colspan="2"><a href="#postcode">postcode</a></td><td>String</td></tr><tr><td colspan="2"><a href="#plaats">plaats</a></td><td>String</td></tr></tbody></table>

<hr />

## straat

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>Description</th>
      <td colspan="2">Straatnaam</td>
    </tr>
    <tr><th>Type</th><td colspan="2">String</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>
    <tr>
      <th>Examples</th>
      <td colspan="2"><li>Waldeck Pyrmontsingel</li></td>
    </tr>
  </tbody>
</table>

## huisnummer

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>Description</th>
      <td colspan="2">Huisnummer</td>
    </tr>
    <tr><th>Type</th><td colspan="2">Number</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>
    <tr>
      <th>Examples</th>
      <td colspan="2"><li>12</li></td>
    </tr>
  </tbody>
</table>

## postcode

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>Description</th>
      <td colspan="2">Postcode</td>
    </tr>
    <tr><th>Type</th><td colspan="2">String</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>
    <tr>
      <th>Examples</th>
      <td colspan="2"><li>6521 BC</li></td>
    </tr>
  </tbody>
</table>

## plaats

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>Description</th>
      <td colspan="2">Plaats</td>
    </tr>
    <tr><th>Type</th><td colspan="2">String</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>
    <tr>
      <th>Examples</th>
      <td colspan="2"><li>Nijmegen</li></td>
    </tr>
  </tbody>
</table>

<hr />

## Schema

```
{
    "$schema": "https://json-schema.org/draft/2020-12/schema",
    "$id": "https://schemas.don.apps.digilab.network/demo/demo/adres",
    "title": "Adres",
    "description": "Adres van een brouwerij",
    "type": "object",
    "properties": {
        "straat": {
            "type": "string",
            "description": "Straatnaam",
            "examples": [
                "Waldeck Pyrmontsingel"
            ]
        },
        "huisnummer": {
            "type": "number",
            "description": "Huisnummer",
            "examples": [
                12
            ]
        },
        "postcode": {
            "type": "string",
            "description": "Postcode",
            "examples": [
                "6521 BC"
            ]
        },
        "plaats": {
            "type": "string",
            "description": "Plaats",
            "examples": [
                "Nijmegen"
            ]
        }
    },
    "required": [
        "straat",
        "huisnummer",
        "postcode",
        "plaats"
    ],
    "additionalProperties": false
}
```
