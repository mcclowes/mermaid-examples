# mermaid-examples

## Default sequence diagram

```mermaid
sequenceDiagram
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
    Alice-)John: See you later!
```

## Flow chart

```mermaid
graph TD;
    subgraph Accounting
    A[Accounting]-->B{Skip?};
    B-->C[Accounting consent];
    C-->D[Accounting auth];
    D-->E[Accounting success];
    end
    subgraph Banking
    E-->F[Banking]
    B-->F
    F-->G{Skip?};
    G-->H[Banking consent];
    H-->I[Banking auth];
    I-->J[Banking success];
    end
    J-->K[Overview]
    G-->K
```




# Other non-mermaid cool stuff
https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
