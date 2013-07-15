# Replin

Replin is a utility to expose any commonjs module to a repl context

# Usage

To repl into your module, just supply the path like this;

    replin ./server

You can also repl into modules installed with npm. Replin will attempt to find
a local module by the supplied name, and fallback to a straight require.

    replin express