# adlpz / HTML Compressor

This is a fork of [darkdelphin/Html-compressor](https://github.com/darkdelphin/Html-compressor) with added
support for output customization.

For support and reference visit the original repository.

## Setting up output

Output is controlled by two variables you can set up in your Sublime's configuration

    "htmlcompressor_output_directory" : "." 

Set the output directory. Defaults to the current directory.

    "htmlcompressor_output_filename" : "${file_base_name}.min.${file_extension}"

Set the output file name. Defaults to the default configuration of html-compressor, min.html extension.