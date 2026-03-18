
# Brouwerij

<p>De brouwerij, inclusief naam, grootte en adres</p>

<table>
<tbody>
<tr><th>$id</th><td>https://schemas.don.apps.digilab.network/demo/demo/brouwerij</td></tr>
<tr><th>$schema</th><td>https://json-schema.org/draft/2020-12/schema</td></tr>
</tbody>
</table>

## Properties

<table class="jssd-properties-table"><thead><tr><th colspan="2">Name</th><th>Type</th></tr></thead><tbody><tr><td colspan="2"><a href="#id">id</a></td><td>String</td></tr><tr><td colspan="2"><a href="#naam">naam</a></td><td>String</td></tr><tr><td colspan="2"><a href="#grootte">grootte</a></td><td>String</td></tr><tr><td colspan="2"><a href="#adres">adres</a></td><td>Object</td></tr></tbody></table>

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
      <td colspan="2"><li>046b6c7f-0b8a-43b9-b35d-6489e6daee93</li></td>
    </tr>
  </tbody>
</table>

## naam

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>Description</th>
      <td colspan="2">Naam</td>
    </tr>
    <tr><th>Type</th><td colspan="2">String</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>
    <tr>
      <th>Examples</th>
      <td colspan="2"><li>Brouwtoren</li></td>
    </tr>
  </tbody>
</table>

## grootte

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>Description</th>
      <td colspan="2">Grootte brouwerij (hobby/micro/groot)</td>
    </tr>
    <tr><th>Type</th><td colspan="2">String</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>
    <tr>
      <th>Enum</th>
      <td colspan="2"><ul><li>hobby</li><li>micro</li><li>groot</li></ul></td>
    </tr><tr>
      <th>Examples</th>
      <td colspan="2"><li>micro</li></td>
    </tr>
  </tbody>
</table>

## adres

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>$id</th>
      <td colspan="2">https://schemas.don.apps.digilab.network/demo/demo/adres</td>
    </tr>
    <tr>
      <th>Title</th>
      <td colspan="2">Adres</td>
    </tr>
    <tr>
      <th>Description</th>
      <td colspan="2">Adres</td>
    </tr>
    <tr><th>Type</th><td colspan="2">Object</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">No</td>
    </tr>

  </tbody>
</table>

### Properties

  <table class="jssd-properties-table"><thead><tr><th colspan="2">Name</th><th>Type</th></tr></thead><tbody><tr><td colspan="2"><a href="#adresstraat">straat</a></td><td>String</td></tr><tr><td colspan="2"><a href="#adreshuisnummer">huisnummer</a></td><td>Number</td></tr><tr><td colspan="2"><a href="#adrespostcode">postcode</a></td><td>String</td></tr><tr><td colspan="2"><a href="#adresplaats">plaats</a></td><td>String</td></tr></tbody></table>

### adres.straat

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

### adres.huisnummer

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

### adres.postcode

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

### adres.plaats

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
    "$id": "https://schemas.don.apps.digilab.network/demo/demo/brouwerij",
    "title": "Brouwerij",
    "description": "De brouwerij, inclusief naam, grootte en adres",
    "type": "object",
    "properties": {
        "id": {
            "type": "string",
            "format": "uuid",
            "description": "Unieke identifier",
            "examples": [
                "046b6c7f-0b8a-43b9-b35d-6489e6daee93"
            ]
        },
        "naam": {
            "type": "string",
            "description": "Naam",
            "examples": [
                "Brouwtoren"
            ]
        },
        "grootte": {
            "type": "string",
            "enum": [
                "hobby",
                "micro",
                "groot"
            ],
            "description": "Grootte brouwerij (hobby/micro/groot)",
            "examples": [
                "micro"
            ]
        },
        "adres": {
            "$ref": "https://schemas.don.apps.digilab.network/demo/demo/adres"
        }
    },
    "required": [
        "id",
        "naam",
        "grootte"
    ],
    "additionalProperties": false
}
```
