<h2>Screenshot</h2>
<img src="./ProjectSnap.png" />
<h3>Blocks</h3>
<img src="./Meraki.jpg" />

<h3>Solution</h3>
<pre>
"solution": {
    "targets": [
      {
        "targetIndex": 0
      },
      {
        "targetIndex": 1,
        "blocks": [
          {
            "opcode": "event_whenflagclicked",
            "topLevel":true
          },
          {
            "opcode": "motion_turnright",
            "inputs": { "DEGREES": [1, [4, "*"]] }
          },
          {
            "opcode": "event_whenkeypressed",
            "topLevel":true
          },
          {
            "opcode": "motion_turnleft",
            "inputs": { "DEGREES": [1, [4, "*"]] }
          }
        ]
      }
    ]
  }
</pre>