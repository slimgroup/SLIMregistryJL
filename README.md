# SLIM Registry for Julia Packages #

The registry with our most commonly used packages that are not in General Julia registry.

## Add Using Pkg  package ##

	Pkg.Registry.add(RegistrySpec(url=“https://github.com/slimgroup/SLIMregistryJL.git”))

## Add Using Package Manager ']' ##

	registry add https://github.com/slimgroup/SLIMregistryJL.git

## Notes: ##

- Check Registry.toml for Registered Packages


