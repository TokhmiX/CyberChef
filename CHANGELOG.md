# Changelog

## Versioning

CyberChef uses the [semver](https://semver.org/) system to manage versioning: `<MAJOR>.<MINOR>.<PATCH>`.

- MAJOR version changes represent a significant change to the fundamental architecture of CyberChef and may (but don't always) make breaking changes that are not backwards compatible.
- MINOR version changes usually mean the addition of new operations or reasonably significant new features.
- PATCH versions are used for bug fixes and any other small tweaks that modify or improve existing capabilities.

All major and minor version changes will be documented in this file. Details of patch-level version changes can be found in [commit messages](https://github.com/gchq/CyberChef/commits/master).


## Details

### [9.39.0] - 2022-06-09
- Added 'ELF Info' operation [@n1073645] | [#1364]

### [9.38.0] - 2022-05-30
- Added 'Parse TCP' operation [@n1474335] | [a895d1d]

### [9.37.0] - 2022-03-29
- 'SM4 Encrypt' and 'SM4 Decrypt' operations added [@swesven] | [#1189]
- NoPadding options added for CBC and ECB modes in AES, DES and Triple DES Decrypt operations [@swesven] | [#1189]

### [9.36.0] - 2022-03-29
- 'SIGABA' operation added [@hettysymes] | [#934]

### [9.35.0] - 2022-03-28
- 'To Base45' and 'From Base45' operations added [@t-8ch] | [#1242]

### [9.34.0] - 2022-03-28
- 'Get All Casings' operation added [@n1073645] | [#1065]

### [9.33.0] - 2022-03-25
- Updated to support Node 17 [@n1474335] [@john19696] [@t-8ch] | [[#1326] [#1313] [#1244]
- Improved CJS and ESM module support [@d98762625] | [#1037]

### [9.32.0] - 2021-08-18
- 'Protobuf Encode' operation added and decode operation modified to allow decoding with full and partial schemas [@n1474335] | [dd18e52]

### [9.31.0] - 2021-08-10
- 'HASSH Client Fingerprint' and 'HASSH Server Fingerprint' operations added [@n1474335] | [e9ca4dc]

### [9.30.0] - 2021-08-10
- 'JA3S Fingerprint' operation added [@n1474335] | [289a417]

### [9.29.0] - 2021-07-28
- 'JA3 Fingerprint' operation added [@n1474335] | [9a33498]

### [9.28.0] - 2021-03-26
- 'CBOR Encode' and 'CBOR Decode' operations added [@Danh4] | [#999]

### [9.27.0] - 2021-02-12
- 'Fuzzy Match' operation added [@n1474335] | [8ad18b]

### [9.26.0] - 2021-02-11
- 'Get Time' operation added [@n1073645] [@n1474335] | [#1045]

### [9.25.0] - 2021-02-11
- 'Extract ID3' operation added [@n1073645] [@n1474335] | [#1006]

### [9.24.0] - 2021-02-02
- 'SM3' hashing function added along with more configuration options for other hashing operations [@n1073645] [@n1474335] | [#1022]

### [9.23.0] - 2021-02-01
- Various RSA operations added to encrypt, decrypt, sign, verify and generate keys [@mattnotmitt] [@GCHQ77703] | [#652]

### [9.22.0] - 2021-02-01
- 'Unicode Text Format' operation added [@mattnotmitt] | [#1083]

### [9.21.0] - 2020-06-12
- Node API now exports `magic` operation [@d98762625] | [#1049]

### [9.20.0] - 2020-03-27
- 'Parse ObjectID Timestamp' operation added [@dmfj] | [#987]

### [9.19.0] - 2020-03-24
- Improvements to the 'Magic' operation, allowing it to recognise more data formats and provide more accurate results [@n1073645] [@n1474335] | [#966] [b765534b](https://github.com/gchq/CyberChef/commit/b765534b8b2a0454a5132a0a52d1d8844bcbdaaa)

### [9.18.0] - 2020-03-13
- 'Convert to NATO alphabet' operation added [@MarvinJWendt] | [#674]

### [9.17.0] - 2020-03-13
- 'Generate Image' operation added [@pointhi] | [#683]

### [9.16.0] - 2020-03-06
- 'Colossus' operation added [@VirtualColossus] | [#917]

### [9.15.0] - 2020-03-05
- 'CipherSaber2 Encrypt' and 'CipherSaber2 Decrypt' operations added [@n1073645] | [#952]

### [9.14.0] - 2020-03-05
- 'Luhn Checksum' operation added [@n1073645] | [#965]

### [9.13.0] - 2020-02-13
- 'Rail Fence Cipher Encode' and 'Rail Fence Cipher Decode' operations added [@Flavsditz] | [#948]

### [9.12.0] - 2019-12-20
- 'Normalise Unicode' operation added [@matthieuxyz] | [#912]

### [9.11.0] - 2019-11-06
- Implemented CFB, OFB, and CTR modes for Blowfish operations [@cbeuw] | [#653]

### [9.10.0] - 2019-11-06
- 'Lorenz' operation added [@VirtualColossus] | [#528]

### [9.9.0] - 2019-11-01
- Added support for 109 more character encodings [@n1474335]

### [9.8.0] - 2019-10-31
- 'Avro to JSON' operation added [@jarrodconnolly] | [#865]

### [9.7.0] - 2019-09-13
- 'Optical Character Recognition' operation added [@MShwed] [@n1474335] | [#632]

### [9.6.0] - 2019-09-04
- 'Bacon Cipher Encode' and 'Bacon Cipher Decode' operations added [@kassi] | [#500]

### [9.5.0] - 2019-09-04
- Various Steganography operations added: 'Extract LSB', 'Extract RGBA', 'Randomize Colour Palette', and 'View Bit Plane' [@Ge0rg3] | [#625]

### [9.4.0] - 2019-08-30
- 'Render Markdown' operation added [@j433866] | [#627]

### [9.3.0] - 2019-08-30
- 'Show on map' operation added [@j433866] | [#477]

### [9.2.0] - 2019-08-23
- 'Parse UDP' operation added [@h345983745] | [#614]

### [9.1.0] - 2019-08-22
- 'Parse SSH Host Key' operation added [@j433866] | [#595]
- 'Defang IP Addresses' operation added [@h345983745] | [#556]

## [9.0.0] - 2019-07-09
- [Multiple inputs](https://github.com/gchq/CyberChef/wiki/Multiple-Inputs) are now supported in the main web UI, allowing you to upload and process multiple files at once [@j433866] | [#566]
- A [Node.js API](https://github.com/gchq/CyberChef/wiki/Node-API) has been implemented, meaning that CyberChef can now be used as a library, either to provide specific operations, or an entire baking environment [@d98762625] | [#291]
- A [read-eval-print loop (REPL)](https://github.com/gchq/CyberChef/wiki/Node-API#repl) is also included to enable prototyping and experimentation with the API [@d98762625] | [#291]
- Light and dark Solarized themes added [@j433866] | [#566]

<details>
    <summary>Click to expand v8 minor versions</summary>

### [8.38.0] - 2019-07-03
- 'Streebog' and 'GOST hash' operations added [@MShwed] [@n1474335] | [#530]

### [8.37.0] - 2019-07-03
- 'CRC-8 Checksum' operation added [@MShwed] | [#591]

### [8.36.0] - 2019-07-03
- 'PGP Verify' operation added [@artemisbot] | [#585]

### [8.35.0] - 2019-07-03
- 'Sharpen Image', 'Convert Image Format' and 'Add Text To Image' operations added [@j433866] | [#515]

### [8.34.0] - 2019-06-28
- Various new visualisations added to the 'Entropy' operation [@MShwed] | [#535]
- Efficiency improvements made to the 'Entropy' operation for large file support [@n1474335]

### [8.33.0] - 2019-06-27
- 'Bzip2 Compress' operation added and 'Bzip2 Decompress' operation greatly improved [@artemisbot] | [#531]

### [8.32.0] - 2019-06-27
- 'Index of Coincidence' operation added [@Ge0rg3] | [#571]

### [8.31.0] - 2019-04-12
- The downloadable version of CyberChef is now a .zip file containing separate modules rather than a single .htm file. It is still completely standalone and will not make any external network requests. This change reduces the complexity of the build process significantly. [@n1474335]

### [8.30.0] - 2019-04-12
- 'Decode Protobuf' operation added [@n1474335] | [#533]

### [8.29.0] - 2019-03-31
- 'BLAKE2s' and 'BLAKE2b' hashing operations added [@h345983745] | [#525]

### [8.28.0] - 2019-03-31
- 'Heatmap Chart', 'Hex Density Chart', 'Scatter Chart' and 'Series Chart' operation added [@artemisbot] [@tlwr] | [#496] [#143]

### [8.27.0] - 2019-03-14
- 'Enigma', 'Typex', 'Bombe' and 'Multiple Bombe' operations added [@s2224834] | [#516]
- See [this wiki article](https://github.com/gchq/CyberChef/wiki/Enigma,-the-Bombe,-and-Typex) for a full explanation of these operations.
- New Bombe-style loading animation added for long-running operations [@n1474335]
- New operation argument types added: `populateMultiOption` and `argSelector` [@n1474335]

### [8.26.0] - 2019-03-09
- Various image manipulation operations added [@j433866] | [#506]

### [8.25.0] - 2019-03-09
- 'Extract Files' operation added and more file formats supported [@n1474335] | [#440]

### [8.24.0] - 2019-02-08
- 'DNS over HTTPS' operation added [@h345983745] | [#489]

### [8.23.1] - 2019-01-18
- 'Convert co-ordinate format' operation added [@j433866] | [#476]

### [8.23.0] - 2019-01-18
- 'YARA Rules' operation added [@artemisbot] | [#468]

### [8.22.0] - 2019-01-10
- 'Subsection' operation added [@j433866] | [#467]

### [8.21.0] - 2019-01-10
- 'To Case Insensitive Regex' and 'From Case Insensitive Regex' operations added [@masq] | [#461]

### [8.20.0] - 2019-01-09
- 'Generate Lorem Ipsum' operation added [@klaxon1] | [#455]

### [8.19.0] - 2018-12-30
- UI test suite added to confirm that the app loads correctly in a reasonable time and that various operations from each module can be run [@n1474335] | [#458]

### [8.18.0] - 2018-12-26
- 'Split Colour Channels' operation added [@artemisbot] | [#449]

### [8.17.0] - 2018-12-25
- 'Generate QR Code' and 'Parse QR Code' operations added [@j433866] | [#448]

### [8.16.0] - 2018-12-19
- 'Play Media' operation added [@anthony-arnold] | [#446]

### [8.15.0] - 2018-12-18
- 'Text Encoding Brute Force' operation added [@Cynser] | [#439]

### [8.14.0] - 2018-12-18
- 'To Base62' and 'From Base62' operations added [@tcode2k16] | [#443]

### [8.13.0] - 2018-12-15
- 'A1Z26 Cipher Encode' and 'A1Z26 Cipher Decode' operations added [@jarmovanlenthe] | [#441]

### [8.12.0] - 2018-11-21
- 'Citrix CTX1 Encode' and 'Citrix CTX1 Decode' operations added [@bwhitn] | [#428]

### [8.11.0] - 2018-11-13
- 'CSV to JSON' and 'JSON to CSV' operations added [@n1474335] | [#277]

### [8.10.0] - 2018-11-07
- 'Remove Diacritics' operation added [@klaxon1] | [#387]

### [8.9.0] - 2018-11-07
- 'Defang URL' operation added [@arnydo] | [#394]

### [8.8.0] - 2018-10-10
- 'Parse TLV' operation added [@GCHQ77703] | [#351]

### [8.7.0] - 2018-08-31
- 'JWT Sign', 'JWT Verify' and 'JWT Decode' operations added [@GCHQ77703] | [#348]

### [8.6.0] - 2018-08-29
- 'To Geohash' and 'From Geohash' operations added [@GCHQ77703] | [#344]

### [8.5.0] - 2018-08-23
- 'To Braille' and 'From Braille' operations added [@n1474335] | [#255]

### [8.4.0] - 2018-08-23
- 'To Base85' and 'From Base85' operations added [@PenguinGeorge] | [#340]

### [8.3.0] - 2018-08-21
- 'To MessagePack' and 'From MessagePack' operations added [@artemisbot] | [#338]

### [8.2.0] - 2018-08-21
- Information links added to most operations, accessible in the description popover [@PenguinGeorge] | [#298]

### [8.1.0] - 2018-08-19
- 'Dechunk HTTP response' operation added [@sevzero] | [#311]

</details>

## [8.0.0] - 2018-08-05
- Codebase rewritten using [ES modules](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/) and [classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes) [@n1474335] [@d98762625] [@artemisbot] [@picapi] | [#284]
- Operation architecture restructured to make adding new operations a lot simpler [@n1474335] | [#284]
- A script has been added to aid in the creation of new operations by running `npm run newop` [@n1474335] | [#284]
- 'Magic' operation added - [automated detection of encoded data](https://github.com/gchq/CyberChef/wiki/Automatic-detection-of-encoded-data-using-CyberChef-Magic) [@n1474335] | [#239]
- UI updated to use [Bootstrap Material Design](https://fezvrasta.github.io/bootstrap-material-design/) [@n1474335] | [#248]
- `JSON`, `File` and `List<File>` Dish types added [@n1474335] | [#284]
- `OperationError` type added for better handling of errors thrown by operations [@d98762625] | [#296]
- A `present()` method has been added, allowing operations to pass machine-friendly data to subsequent operations whilst presenting human-friendly data to the user [@n1474335] | [#284]
- Set operations added [@d98762625] | [#281]
- 'To Table' operation added [@JustAnotherMark] | [#294]
- 'Haversine distance' operation added [@Dachande663] | [#325]
- Started keeping a changelog [@n1474335]

## [7.0.0] - 2017-12-28
- Added support for loading, processing and downloading files up to 500MB [@n1474335] | [#224]

## [6.0.0] - 2017-09-19
- Threading support added. All recipe processing moved into a [Web Worker](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers) to increase performance and to allow long-running operations to be cancelled [@n1474335] | [#173]
- Module system created so that operations relying on large libraries can be downloaded separately as required, reducing the initial loading time for the app [@n1474335] | [#173]

## [5.0.0] - 2017-03-30
-  Webpack build process configured with Babel transpilation and ES6 imports and exports [@n1474335] | [#95]

## [4.0.0] - 2016-11-28
-  Initial open source commit [@n1474335] | [b1d73a72](https://github.com/gchq/CyberChef/commit/b1d73a725dc7ab9fb7eb789296efd2b7e4b08306)



[9.39.0]: https://github.com/gchq/CyberChef/releases/tag/v9.39.0
[9.38.0]: https://github.com/gchq/CyberChef/releases/tag/v9.38.0
[9.37.0]: https://github.com/gchq/CyberChef/releases/tag/v9.37.0
[9.36.0]: https://github.com/gchq/CyberChef/releases/tag/v9.36.0
[9.35.0]: https://github.com/gchq/CyberChef/releases/tag/v9.35.0
[9.34.0]: https://github.com/gchq/CyberChef/releases/tag/v9.34.0
[9.33.0]: https://github.com/gchq/CyberChef/releases/tag/v9.33.0
[9.32.0]: https://github.com/gchq/CyberChef/releases/tag/v9.32.0
[9.31.0]: https://github.com/gchq/CyberChef/releases/tag/v9.31.0
[9.30.0]: https://github.com/gchq/CyberChef/releases/tag/v9.30.0
[9.29.0]: https://github.com/gchq/CyberChef/releases/tag/v9.29.0
[9.28.0]: https://github.com/gchq/CyberChef/releases/tag/v9.28.0
[9.27.0]: https://github.com/gchq/CyberChef/releases/tag/v9.27.0
[9.26.0]: https://github.com/gchq/CyberChef/releases/tag/v9.26.0
[9.25.0]: https://github.com/gchq/CyberChef/releases/tag/v9.25.0
[9.24.0]: https://github.com/gchq/CyberChef/releases/tag/v9.24.0
[9.23.0]: https://github.com/gchq/CyberChef/releases/tag/v9.23.0
[9.22.0]: https://github.com/gchq/CyberChef/releases/tag/v9.22.0
[9.21.0]: https://github.com/gchq/CyberChef/releases/tag/v9.21.0
[9.20.0]: https://github.com/gchq/CyberChef/releases/tag/v9.20.0
[9.19.0]: https://github.com/gchq/CyberChef/releases/tag/v9.19.0
[9.18.0]: https://github.com/gchq/CyberChef/releases/tag/v9.18.0
[9.17.0]: https://github.com/gchq/CyberChef/releases/tag/v9.17.0
[9.16.0]: https://github.com/gchq/CyberChef/releases/tag/v9.16.0
[9.15.0]: https://github.com/gchq/CyberChef/releases/tag/v9.15.0
[9.14.0]: https://github.com/gchq/CyberChef/releases/tag/v9.14.0
[9.13.0]: https://github.com/gchq/CyberChef/releases/tag/v9.13.0
[9.12.0]: https://github.com/gchq/CyberChef/releases/tag/v9.12.0
[9.11.0]: https://github.com/gchq/CyberChef/releases/tag/v9.11.0
[9.10.0]: https://github.com/gchq/CyberChef/releases/tag/v9.10.0
[9.9.0]: https://github.com/gchq/CyberChef/releases/tag/v9.9.0
[9.8.0]: https://github.com/gchq/CyberChef/releases/tag/v9.8.0
[9.7.0]: https://github.com/gchq/CyberChef/releases/tag/v9.7.0
[9.6.0]: https://github.com/gchq/CyberChef/releases/tag/v9.6.0
[9.5.0]: https://github.com/gchq/CyberChef/releases/tag/v9.5.0
[9.4.0]: https://github.com/gchq/CyberChef/releases/tag/v9.4.0
[9.3.0]: https://github.com/gchq/CyberChef/releases/tag/v9.3.0
[9.2.0]: https://github.com/gchq/CyberChef/releases/tag/v9.2.0
[9.1.0]: https://github.com/gchq/CyberChef/releases/tag/v9.1.0
[9.0.0]: https://github.com/gchq/CyberChef/releases/tag/v9.0.0
[8.38.0]: https://github.com/gchq/CyberChef/releases/tag/v8.38.0
[8.37.0]: https://github.com/gchq/CyberChef/releases/tag/v8.37.0
[8.36.0]: https://github.com/gchq/CyberChef/releases/tag/v8.36.0
[8.35.0]: https://github.com/gchq/CyberChef/releases/tag/v8.35.0
[8.34.0]: https://github.com/gchq/CyberChef/releases/tag/v8.34.0
[8.33.0]: https://github.com/gchq/CyberChef/releases/tag/v8.33.0
[8.32.0]: https://github.com/gchq/CyberChef/releases/tag/v8.32.0
[8.31.0]: https://github.com/gchq/CyberChef/releases/tag/v8.31.0
[8.30.0]: https://github.com/gchq/CyberChef/releases/tag/v8.30.0
[8.29.0]: https://github.com/gchq/CyberChef/releases/tag/v8.29.0
[8.28.0]: https://github.com/gchq/CyberChef/releases/tag/v8.28.0
[8.27.0]: https://github.com/gchq/CyberChef/releases/tag/v8.27.0
[8.26.0]: https://github.com/gchq/CyberChef/releases/tag/v8.26.0
[8.25.0]: https://github.com/gchq/CyberChef/releases/tag/v8.25.0
[8.24.0]: https://github.com/gchq/CyberChef/releases/tag/v8.24.0
[8.23.1]: https://github.com/gchq/CyberChef/releases/tag/v8.23.1
[8.23.0]: https://github.com/gchq/CyberChef/releases/tag/v8.23.0
[8.22.0]: https://github.com/gchq/CyberChef/releases/tag/v8.22.0
[8.21.0]: https://github.com/gchq/CyberChef/releases/tag/v8.21.0
[8.20.0]: https://github.com/gchq/CyberChef/releases/tag/v8.20.0
[8.19.0]: https://github.com/gchq/CyberChef/releases/tag/v8.19.0
[8.18.0]: https://github.com/gchq/CyberChef/releases/tag/v8.18.0
[8.17.0]: https://github.com/gchq/CyberChef/releases/tag/v8.17.0
[8.16.0]: https://github.com/gchq/CyberChef/releases/tag/v8.16.0
[8.15.0]: https://github.com/gchq/CyberChef/releases/tag/v8.15.0
[8.14.0]: https://github.com/gchq/CyberChef/releases/tag/v8.14.0
[8.13.0]: https://github.com/gchq/CyberChef/releases/tag/v8.13.0
[8.12.0]: https://github.com/gchq/CyberChef/releases/tag/v8.12.0
[8.11.0]: https://github.com/gchq/CyberChef/releases/tag/v8.11.0
[8.10.0]: https://github.com/gchq/CyberChef/releases/tag/v8.10.0
[8.9.0]: https://github.com/gchq/CyberChef/releases/tag/v8.9.0
[8.8.0]: https://github.com/gchq/CyberChef/releases/tag/v8.8.0
[8.7.0]: https://github.com/gchq/CyberChef/releases/tag/v8.7.0
[8.6.0]: https://github.com/gchq/CyberChef/releases/tag/v8.6.0
[8.5.0]: https://github.com/gchq/CyberChef/releases/tag/v8.5.0
[8.4.0]: https://github.com/gchq/CyberChef/releases/tag/v8.4.0
[8.3.0]: https://github.com/gchq/CyberChef/releases/tag/v8.3.0
[8.2.0]: https://github.com/gchq/CyberChef/releases/tag/v8.2.0
[8.1.0]: https://github.com/gchq/CyberChef/releases/tag/v8.1.0
[8.0.0]: https://github.com/gchq/CyberChef/releases/tag/v8.0.0
[7.0.0]: https://github.com/gchq/CyberChef/releases/tag/v7.0.0
[6.0.0]: https://github.com/gchq/CyberChef/releases/tag/v6.0.0
[5.0.0]: https://github.com/gchq/CyberChef/releases/tag/v5.0.0
[4.0.0]: https://github.com/gchq/CyberChef/commit/b1d73a725dc7ab9fb7eb789296efd2b7e4b08306

[@n1474335]: https://github.com/n1474335
[@d98762625]: https://github.com/d98762625
[@j433866]: https://github.com/j433866
[@n1073645]: https://github.com/n1073645
[@GCHQ77703]: https://github.com/GCHQ77703
[@h345983745]: https://github.com/h345983745
[@s2224834]: https://github.com/s2224834
[@artemisbot]: https://github.com/artemisbot
[@tlwr]: https://github.com/tlwr
[@picapi]: https://github.com/picapi
[@Dachande663]: https://github.com/Dachande663
[@JustAnotherMark]: https://github.com/JustAnotherMark
[@sevzero]: https://github.com/sevzero
[@PenguinGeorge]: https://github.com/PenguinGeorge
[@arnydo]: https://github.com/arnydo
[@klaxon1]: https://github.com/klaxon1
[@bwhitn]: https://github.com/bwhitn
[@jarmovanlenthe]: https://github.com/jarmovanlenthe
[@tcode2k16]: https://github.com/tcode2k16
[@Cynser]: https://github.com/Cynser
[@anthony-arnold]: https://github.com/anthony-arnold
[@masq]: https://github.com/masq
[@Ge0rg3]: https://github.com/Ge0rg3
[@MShwed]: https://github.com/MShwed
[@kassi]: https://github.com/kassi
[@jarrodconnolly]: https://github.com/jarrodconnolly
[@VirtualColossus]: https://github.com/VirtualColossus
[@cbeuw]: https://github.com/cbeuw
[@matthieuxyz]: https://github.com/matthieuxyz
[@Flavsditz]: https://github.com/Flavsditz
[@pointhi]: https://github.com/pointhi
[@MarvinJWendt]: https://github.com/MarvinJWendt
[@dmfj]: https://github.com/dmfj
[@mattnotmitt]: https://github.com/mattnotmitt
[@Danh4]: https://github.com/Danh4
[@john19696]: https://github.com/john19696
[@t-8ch]: https://github.com/t-8ch
[@hettysymes]: https://github.com/hettysymes
[@swesven]: https://github.com/swesven

[8ad18b]: https://github.com/gchq/CyberChef/commit/8ad18bc7db6d9ff184ba3518686293a7685bf7b7
[9a33498]: https://github.com/gchq/CyberChef/commit/9a33498fed26a8df9c9f35f39a78a174bf50a513
[289a417]: https://github.com/gchq/CyberChef/commit/289a417dfb5923de5e1694354ec42a08d9395bfe
[e9ca4dc]: https://github.com/gchq/CyberChef/commit/e9ca4dc9caf98f33fd986431cd400c88082a42b8
[dd18e52]: https://github.com/gchq/CyberChef/commit/dd18e529939078b89867297b181a584e8b2cc7da
[a895d1d]: https://github.com/gchq/CyberChef/commit/a895d1d82a2f92d440a0c5eca2bc7c898107b737

[#95]: https://github.com/gchq/CyberChef/pull/299
[#173]: https://github.com/gchq/CyberChef/pull/173
[#143]: https://github.com/gchq/CyberChef/pull/143
[#224]: https://github.com/gchq/CyberChef/pull/224
[#239]: https://github.com/gchq/CyberChef/pull/239
[#248]: https://github.com/gchq/CyberChef/pull/248
[#255]: https://github.com/gchq/CyberChef/issues/255
[#277]: https://github.com/gchq/CyberChef/issues/277
[#281]: https://github.com/gchq/CyberChef/pull/281
[#284]: https://github.com/gchq/CyberChef/pull/284
[#291]: https://github.com/gchq/CyberChef/pull/291
[#294]: https://github.com/gchq/CyberChef/pull/294
[#296]: https://github.com/gchq/CyberChef/pull/296
[#298]: https://github.com/gchq/CyberChef/pull/298
[#311]: https://github.com/gchq/CyberChef/pull/311
[#325]: https://github.com/gchq/CyberChef/pull/325
[#338]: https://github.com/gchq/CyberChef/pull/338
[#340]: https://github.com/gchq/CyberChef/pull/340
[#344]: https://github.com/gchq/CyberChef/pull/344
[#348]: https://github.com/gchq/CyberChef/pull/348
[#351]: https://github.com/gchq/CyberChef/pull/351
[#387]: https://github.com/gchq/CyberChef/pull/387
[#394]: https://github.com/gchq/CyberChef/pull/394
[#428]: https://github.com/gchq/CyberChef/pull/428
[#439]: https://github.com/gchq/CyberChef/pull/439
[#440]: https://github.com/gchq/CyberChef/pull/440
[#441]: https://github.com/gchq/CyberChef/pull/441
[#443]: https://github.com/gchq/CyberChef/pull/443
[#446]: https://github.com/gchq/CyberChef/pull/446
[#448]: https://github.com/gchq/CyberChef/pull/448
[#449]: https://github.com/gchq/CyberChef/pull/449
[#455]: https://github.com/gchq/CyberChef/pull/455
[#458]: https://github.com/gchq/CyberChef/pull/458
[#461]: https://github.com/gchq/CyberChef/pull/461
[#467]: https://github.com/gchq/CyberChef/pull/467
[#468]: https://github.com/gchq/CyberChef/pull/468
[#476]: https://github.com/gchq/CyberChef/pull/476
[#477]: https://github.com/gchq/CyberChef/pull/477
[#489]: https://github.com/gchq/CyberChef/pull/489
[#496]: https://github.com/gchq/CyberChef/pull/496
[#500]: https://github.com/gchq/CyberChef/pull/500
[#506]: https://github.com/gchq/CyberChef/pull/506
[#515]: https://github.com/gchq/CyberChef/pull/515
[#516]: https://github.com/gchq/CyberChef/pull/516
[#525]: https://github.com/gchq/CyberChef/pull/525
[#528]: https://github.com/gchq/CyberChef/pull/528
[#530]: https://github.com/gchq/CyberChef/pull/530
[#531]: https://github.com/gchq/CyberChef/pull/531
[#533]: https://github.com/gchq/CyberChef/pull/533
[#535]: https://github.com/gchq/CyberChef/pull/535
[#556]: https://github.com/gchq/CyberChef/pull/556
[#566]: https://github.com/gchq/CyberChef/pull/566
[#571]: https://github.com/gchq/CyberChef/pull/571
[#585]: https://github.com/gchq/CyberChef/pull/585
[#591]: https://github.com/gchq/CyberChef/pull/591
[#595]: https://github.com/gchq/CyberChef/pull/595
[#614]: https://github.com/gchq/CyberChef/pull/614
[#625]: https://github.com/gchq/CyberChef/pull/625
[#627]: https://github.com/gchq/CyberChef/pull/627
[#632]: https://github.com/gchq/CyberChef/pull/632
[#652]: https://github.com/gchq/CyberChef/pull/652
[#653]: https://github.com/gchq/CyberChef/pull/653
[#674]: https://github.com/gchq/CyberChef/pull/674
[#683]: https://github.com/gchq/CyberChef/pull/683
[#865]: https://github.com/gchq/CyberChef/pull/865
[#912]: https://github.com/gchq/CyberChef/pull/912
[#917]: https://github.com/gchq/CyberChef/pull/917
[#934]: https://github.com/gchq/CyberChef/pull/934
[#948]: https://github.com/gchq/CyberChef/pull/948
[#952]: https://github.com/gchq/CyberChef/pull/952
[#965]: https://github.com/gchq/CyberChef/pull/965
[#966]: https://github.com/gchq/CyberChef/pull/966
[#987]: https://github.com/gchq/CyberChef/pull/987
[#999]: https://github.com/gchq/CyberChef/pull/999
[#1006]: https://github.com/gchq/CyberChef/pull/1006
[#1022]: https://github.com/gchq/CyberChef/pull/1022
[#1037]: https://github.com/gchq/CyberChef/pull/1037
[#1045]: https://github.com/gchq/CyberChef/pull/1045
[#1049]: https://github.com/gchq/CyberChef/pull/1049
[#1065]: https://github.com/gchq/CyberChef/pull/1065
[#1083]: https://github.com/gchq/CyberChef/pull/1083
[#1189]: https://github.com/gchq/CyberChef/pull/1189
[#1242]: https://github.com/gchq/CyberChef/pull/1242
[#1244]: https://github.com/gchq/CyberChef/pull/1244
[#1313]: https://github.com/gchq/CyberChef/pull/1313
[#1326]: https://github.com/gchq/CyberChef/pull/1326
[#1364]: https://github.com/gchq/CyberChef/pull/1364
