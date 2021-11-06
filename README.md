# js-ipfs-core-min

Redirect to minified/bundled `index.min.js` of [ipfs-core](https://github.com/ipfs/js-ipfs)

* About IPFS: [https://ipfs.io/](https://ipfs.io/)
* Examples: [https://github.com/ipfs-examples/js-ipfs-examples](https://github.com/ipfs-examples/js-ipfs-examples)

## Usage

```bash
npm install ipfs-core ipfs-core-min
```

then in the application:

```javascript
import { create as createIpfs } from 'ipfs-core-min';
console.log({ createIpfs });
const ipfs = await createIpfs();
// ...
```

### Note

on 2021/11/7, this works with `ipfs-core@0.11.1` which has `/index.min.js`
