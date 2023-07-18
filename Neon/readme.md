<h2>Screenshot</h2>
<img src="./ProjectSnap.png" />
<h3>Blocks</h3>
<img src="./Neon.jpg" />

<h3>Solution</h3>
<pre>
"solution": {
    "targets": [
      {
        "targetIndex": 0,
        "costumes": [
          {
            "name": "Neon Tunnel"
          }
        ]
      },
      {
        "targetIndex": 1,
        "blocks": [
          {
            "opcode": "event_whenkeypressed",
            "topLevel": true
          },
          {
            "opcode": "looks_changesizeby",
            "inputs": { "CHANGE": [1, [4, "*"]] }
          }
        ]
      }
    ]
  }
</pre>