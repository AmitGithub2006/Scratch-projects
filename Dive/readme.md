<h2>Screenshot</h2>
<img src="./ProjectSnap.png" />
<h3>Blocks</h3>
<img src="./Dive.jpg" />

<h3>Solution</h3>
<pre>
"solution": {
    "targets": [
      {
        "targetIndex": 0,
        "costumes": [
          {
            "name": "Pool"
          },
          {
             "name": "Underwater 1"
          }
        ]
      },
      {
        "targetIndex": 1,
        "blocks": [
          {
            "opcode": "event_whenkeypressed",
            "topLevel":true,
            "fields": { "KEY_OPTION": ["*", null] }
          },
          {
            "opcode": "looks_changesizeby",
            "inputs": { "CHANGE": [1, [4, "*"]] }
          }
        ]
      },
      {
        "targetIndex": 2,
        "blocks":[],
        "name": "Diver2"
      }
    ]
  }
</pre>