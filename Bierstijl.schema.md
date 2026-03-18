
# Bierstijl

<p>De bierstijl van een bier, bijvoorbeeld &#x27;Quadrupel&#x27; of &#x27;Weizen Tripel&#x27;</p>

<table>
<tbody>
<tr><th>$id</th><td>https://schemas.don.apps.digilab.network/demo/demo/bierstijl</td></tr>
<tr><th>$schema</th><td>https://json-schema.org/draft/2020-12/schema</td></tr>
</tbody>
</table>

## Properties

<table class="jssd-properties-table"><thead><tr><th colspan="2">Name</th><th>Type</th></tr></thead><tbody><tr><td colspan="2"><a href="#id">id</a></td><td>String</td></tr><tr><td colspan="2"><a href="#naam">naam</a></td><td>String</td></tr></tbody></table>

<hr />

## id

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>Description</th>
      <td colspan="2">Unieke identifier</td>
    </tr>
    <tr><th>Type</th><td colspan="2">String</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>
    <tr>
      <th>Format</th>
      <td colspan="2">uuid</td>
    </tr><tr>
      <th>Examples</th>
      <td colspan="2"><li>046b6c7f-0b8a-43b9-b35d-6489e6daee91</li></td>
    </tr>
  </tbody>
</table>

## naam

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>Description</th>
      <td colspan="2">Naam van de bierstijl</td>
    </tr>
    <tr><th>Type</th><td colspan="2">String</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>
    <tr>
      <th>Examples</th>
      <td colspan="2"><li>Quadrupel</li></td>
    </tr>
  </tbody>
</table>

<hr />

## Schema

```
{
    "$schema": "https://json-schema.org/draft/2020-12/schema",
    "$id": "https://schemas.don.apps.digilab.network/demo/demo/bierstijl",
    "title": "Bierstijl",
    "description": "De bierstijl van een bier, bijvoorbeeld 'Quadrupel' of 'Weizen Tripel'",
    "type": "object",
    "properties": {
        "id": {
            "type": "string",
            "format": "uuid",
            "description": "Unieke identifier",
            "examples": [
                "046b6c7f-0b8a-43b9-b35d-6489e6daee91"
            ]
        },
        "naam": {
            "type": "string",
            "description": "Naam van de bierstijl",
            "examples": [
                "Quadrupel"
            ]
        }
    },
    "required": [
        "id",
        "naam"
    ],
    "additionalProperties": false
}
```
