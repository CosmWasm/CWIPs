# CWIPs

CosmWasm Improvement Proposals (CWIPs, [pronounced "swips"](https://vimeo.com/491116070#t=1608s))
describe standards and record high-level architecture decisions.

## Areas of interest

An incomplete list of areas of interest is:

**Contract development**

- The standard library
- Alternative standard libraries (in Rust and other languages)

**VM**

- The contract-VM interface
- Definition of crypto APIs
- Gas metering
- Performance improvements
- Resource limiting (memory, output data size)

**Concepts and conventions**

- Naming consistency throughout the stack
- The actor model and its implications
- Storage layout
- Client-contract communication

## Contributing

1. Familiarize yourself with the consequences of creating
   [CC0](https://creativecommons.org/publicdomain/zero/1.0/) licensed work.
2. Fork the repository.
3. Add your CWIP to your fork of the repository. There is a [template CWIP here](template.md).
4. Ensure your document is formatted (using `./tools/format.sh`)
5. Submit a Pull Request to CosmWasm's [CWIPs repository](https://github.com/CosmWasm/CWIPs).

Your first PR should be a first draft of the final CWIP. An editor will manually review the first PR
for a new CWIP and assign it a number before merging it. Make sure you include a `discussions-to`
header with the URL to a discussion forum or open GitHub issue where people can discuss the CWIP as
a whole.

### Numbering

Each CWIP has a number. It should be referred to as "CWIP-n" in text, where `n` is the number with
leading zero (e.g. CWIP-15). File names and folder should use `cip-N`, where `N` is a zero padded
four digit representation of the number (e.g. cwip-0015).

### Images

If your CWIP requires images or other supporting files, those should be included in a subdirectory
of the `assets` folder for that CWIP as follows: `assets/cwip-N` (where `N` is to be replaced with
the CWIP number). When linking to an image in the CWIP, use relative links such as
`../assets/cwip-0015/image.png`.
