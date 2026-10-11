# Polp

# Develop

# Release

1. Bump version 
> edit common.props
2. Run (cygwin)
> make clean -f Makefile.polp
3. Run (powershell)
> make build Config=Release -f Makefile.polp

# Deploy
1. Run 
> make deploy -f Makefile.deploy NugetSource=xx
