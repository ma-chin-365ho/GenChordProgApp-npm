# GenChordProgApp-npm
## Chord Progression Generator

---
<p>sample code</p>

* filename : DriverWrapGenChordProgCommon.js
``` 
const cpg = require('chordproggen/WrapGenChordProgCommon');

async function main() {

    var json = await cpg.gen(3,5);
    console.log(json);
}

main();
``` 
* output
``` 
$ node DriverWrapGenChordProgCommon.js
{
  chordProg: 'Am7 | Dm7 | Fmaj7 | Dm7 | Bm7(-5) | Fmaj7 | G7 | G7 | Bm7(-5) | Em',
  tempo: ' 74'
}
```

