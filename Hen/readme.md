<h2>Screenshot</h2>
<img src="./ProjectSnap.png" />
<h3>Blocks</h3>
<img src="./Hen.jpg" />
<img src="./Hen1.jpg" />
<img src="./Hen2.jpg" />

<h3>Solution</h3>
<pre>
"solution": {
    "targets": [
      {
        "targetIndex": 0,
        "costumes": [
          {
            "name": "Forest"
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
            "opcode": "looks_say",
            "inputs": { "MESSAGE": [1, [10, "*"]] }
          }
        ]
      },
      {
        "targetIndex": 2,
        "blocks": []
      },
      {
        "targetIndex": 3,
        "blocks": [
            {
              "opcode": "event_whenflagclicked",
              "topLevel": true
            },
            {
              "opcode": "sound_playuntildone",
              "inputs": { "SOUND_MENU": [1, "*"] }
            },
            {
              "opcode": "sound_sounds_menu",
              "fields": { "SOUND_MENU": ["*", null] }
            }
        ]
      },
      {
        "targetIndex": 4,
        "blocks": [
            {
              "opcode": "event_whenflagclicked",
              "topLevel": true
            },
            {
              "opcode": "motion_movesteps",
              "inputs": { "STEPS": [1, [4, "*"]] }
            }
        ]
      }
    ]
  }
</pre>