Lexicons
========

Add your USAS lexicons (or symlinks thereto) here.

Name them after valid country codes, with the `_sw.usas` extension such that:

 1. They match up to `./templates/references`
 2. The country codes can be used elsewhere (i.e. in the form's `<html lang=...` header)

i.e. `en_sw.usas`, `nl_sw.usas`.

The server expects that lexicons are encoded as ISO-8859-1, in accordance with USAS' loading code (which is not UTF aware).
