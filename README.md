![rawrrHexSticker](https://github.com/fgcz/rawrr/blob/master/rawrr_logo.png)

# rawrr
R interface for Thermo Fisher Scientifc raw files branched from [rawDiag](https://github.com/fgcz/rawDiag). This package wraps the functionality of the [RawFileReader](https://planetorbitrap.com/rawfilereader) .NET assembly. 
rawrr will serve as an entry point for reading Thermo Fisher Scientific instrument files using the [MsRawFileReaderBackend](https://github.com/cpanse/MsBackendRawFileReader) for the Bioconductor [Spectra](https://bioconductor.org/packages/Spectra/) package.
Within the R environment spectra and chromatograms are represented by S3 objects.

## Install

### build package
Please install the latest release from https://github.com/fgcz/rawR/releases according to the provided instructions.


### from source

* install https://planetorbitrap.com/rawfilereader DLL files, e.g., copy file to `/usr/local/lib/RawFileReader/`

* set `export MONO_PATH=/usr/local/lib/RawFileReader/`



## System requirements

* [R](https://cran.r-project.org/) (>= 4.1)

* U.S. language setting 
 
### MS Windows

Make sure that .NET Framework 4.5.1 or higher is installed.

### macOS|Linux

You need to have [Mono](https://www.mono-project.com) installed. Mono is an open source implementation of Microsoft's .NET Framework.

## Manuscripts

https://www.biorxiv.org/content/10.1101/2020.10.30.362533v1

## Blog posts

http://proteomicsnews.blogspot.com/2020/11/raw-mass-spec-data-is-too-pretty-for.html
