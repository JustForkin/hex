<p align="center"><a href="https://lo-th.github.io/hex/"><img src="./assets/icon.svg"/></a></p>

<p align="center">Simple LZMA compressor<br>
use <a href="https://github.com/LZMA-JS/LZMA-JS">LZMA-JS</a> for compression<br><br>
Use this tools to compress any javascript libs or any text file like .OBJ .BVH ...<br>
For example three.min.js = 523ko to 106ko | ammo.js = 1599ko to 265ko<br><br>
You only need extract.js to decompress you script and<br>
add to you webpage or your worker look examples<br><br>

```javascript
extract.load( ['./hex/three.min.hex', './hex/ammo.hex', './hex/bvh.hex'], init, [0,1,2] );
// 0 return javasript main element
// 1 return Blob for worker : extract.get('ammo');
// 2 return textfile for parser : extract.get('bvh'); 
```

<br><br>
<a href="http://lo-th.github.io/hex/">COMPRESOR</a><br></p>