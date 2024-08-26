## Hmmer hmmsearch rust wrapper
Rust wrapper to hmmsearch program in hmmer v3.4 for GSearch software and other purposes. 

#usage
```bash
 ************** initializing logger *****************

Search protein sequences against HMM profiles

Usage: hmmsearch_rs [OPTIONS] --faa <fasta> --hmm <hmm>

Options:
  -f, --faa <fasta>      Path to the faa file containing the protein sequences
  -m, --hmm <hmm>        Path to the HMM file
  -o, --output <output>  Output file to save the search results
  -h, --help             Print help
  -V, --version          Print version

```

We only extract the tabular output format from hmmsearch results for easy parsing. For detailed profile alignment results, please check the orignal hmmer C code. 

# Acknowledgement

Ben J Woodcroft (https://github.com/wwood) for wrapping around hmmer C API and Mustafa Guler (https://github.com/mustafa-guler) for Rust FFI to hmmer v3.4
