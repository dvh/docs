
# Bier

<p>Het specifieke bier dat een brouwerij produceert</p>

<table>
<tbody>
<tr><th>$id</th><td>https://schemas.don.apps.digilab.network/demo/demo/bier</td></tr>
<tr><th>$schema</th><td>https://json-schema.org/draft/2020-12/schema</td></tr>
</tbody>
</table>

## Properties

<table class="jssd-properties-table"><thead><tr><th colspan="2">Name</th><th>Type</th></tr></thead><tbody><tr><td colspan="2"><a href="#id">id</a></td><td>String</td></tr><tr><td colspan="2"><a href="#naam">naam</a></td><td>String</td></tr><tr><td colspan="2"><a href="#alcoholpercentage">alcoholPercentage</a></td><td>Number</td></tr><tr><td colspan="2"><a href="#bierstijl">bierstijl</a></td><td>Object</td></tr><tr><td colspan="2"><a href="#brouwerij">brouwerij</a></td><td>Object</td></tr></tbody></table>

## Example

```
{
    "id": "046b6c7f-0b8a-43b9-b35d-6489e6daee92",
    "naam": "Weizen Tripel",
    "alcoholPercentage": 7.6,
    "bierstijl": {
        "id": "046b6c7f-0b8a-43b9-b35d-6489e6daee91",
        "naam": "Weizen Tripel"
    },
    "brouwerij": {
        "id": "046b6c7f-0b8a-43b9-b35d-6489e6daee90",
        "naam": "Brouwtoren",
        "grootte": "micro",
        "adres": {
            "straat": "Waldeck Pyrmontsingel",
            "huisnummer": 12,
            "postcode": "6521 BC",
            "plaats": "Nijmegen"
        }
    }
}
```

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
      <td colspan="2"><li>046b6c7f-0b8a-43b9-b35d-6489e6daee92</li></td>
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
      <td colspan="2"><li>Weizen Tripel</li></td>
    </tr>
  </tbody>
</table>

## alcoholPercentage

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>Description</th>
      <td colspan="2">Alcoholpercentage</td>
    </tr>
    <tr><th>Type</th><td colspan="2">Number</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>
    <tr>
      <th>Examples</th>
      <td colspan="2"><li>7.6</li></td>
    </tr>
  </tbody>
</table>

## bierstijl

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>$id</th>
      <td colspan="2">https://schemas.don.apps.digilab.network/demo/demo/bierstijl</td>
    </tr>
    <tr>
      <th>Title</th>
      <td colspan="2">Bierstijl</td>
    </tr>
    <tr>
      <th>Description</th>
      <td colspan="2">Bierstijl</td>
    </tr>
    <tr><th>Type</th><td colspan="2">Object</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">Yes</td>
    </tr>

  </tbody>
</table>

### Properties

  <table class="jssd-properties-table"><thead><tr><th colspan="2">Name</th><th>Type</th></tr></thead><tbody><tr><td colspan="2"><a href="#bierstijlid">id</a></td><td>String</td></tr><tr><td colspan="2"><a href="#bierstijlnaam">naam</a></td><td>String</td></tr></tbody></table>

### bierstijl.id

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

### bierstijl.naam

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
      <td colspan="2"><li>Quadrupel</li></td>
    </tr>
  </tbody>
</table>

## brouwerij

<table class="jssd-property-table">
  <tbody>
    <tr>
      <th>$id</th>
      <td colspan="2">https://schemas.don.apps.digilab.network/demo/demo/brouwerij</td>
    </tr>
    <tr>
      <th>Title</th>
      <td colspan="2">Brouwerij</td>
    </tr>
    <tr>
      <th>Description</th>
      <td colspan="2">Brouwerij</td>
    </tr>
    <tr><th>Type</th><td colspan="2">Object</td></tr>
    <tr>
      <th>Required</th>
      <td colspan="2">No</td>
    </tr>

  </tbody>
</table>

### Properties

  <table class="jssd-properties-table"><thead><tr><th colspan="2">Name</th><th>Type</th></tr></thead><tbody><tr><td colspan="2"><a href="#brouwerijid">id</a></td><td>String</td></tr><tr><td colspan="2"><a href="#brouwerijnaam">naam</a></td><td>String</td></tr><tr><td colspan="2"><a href="#brouwerijgrootte">grootte</a></td><td>String</td></tr><tr><td colspan="2"><a href="#brouwerijadres">adres</a></td><td>Object</td></tr></tbody></table>

### brouwerij.id

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

### brouwerij.naam

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

### brouwerij.grootte

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

### brouwerij.adres

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

### brouwerij.adres.straat

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

### brouwerij.adres.huisnummer

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

### brouwerij.adres.postcode

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

### brouwerij.adres.plaats

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
    "$id": "https://schemas.don.apps.digilab.network/demo/demo/bier",
    "title": "Bier",
    "description": "Het specifieke bier dat een brouwerij produceert",
    "type": "object",
    "examples": [
        {
            "id": "046b6c7f-0b8a-43b9-b35d-6489e6daee92",
            "naam": "Weizen Tripel",
            "alcoholPercentage": 7.6,
            "bierstijl": {
                "id": "046b6c7f-0b8a-43b9-b35d-6489e6daee91",
                "naam": "Weizen Tripel"
            },
            "brouwerij": {
                "id": "046b6c7f-0b8a-43b9-b35d-6489e6daee90",
                "naam": "Brouwtoren",
                "grootte": "micro",
                "adres": {
                    "straat": "Waldeck Pyrmontsingel",
                    "huisnummer": 12,
                    "postcode": "6521 BC",
                    "plaats": "Nijmegen"
                }
            }
        }
    ],
    "properties": {
        "id": {
            "type": "string",
            "format": "uuid",
            "description": "Unieke identifier",
            "examples": [
                "046b6c7f-0b8a-43b9-b35d-6489e6daee92"
            ]
        },
        "naam": {
            "type": "string",
            "description": "Naam",
            "examples": [
                "Weizen Tripel"
            ]
        },
        "alcoholPercentage": {
            "type": "number",
            "description": "Alcoholpercentage",
            "examples": [
                7.6
            ]
        },
        "bierstijl": {
            "$ref": "https://schemas.don.apps.digilab.network/demo/demo/bierstijl"
        },
        "brouwerij": {
            "$ref": "https://schemas.don.apps.digilab.network/demo/demo/brouwerij"
        }
    },
    "required": [
        "id",
        "naam",
        "alcoholPercentage",
        "bierstijl"
    ],
    "additionalProperties": false
}
```
