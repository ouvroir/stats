# Julia librairies

## Dataframes
https://dataframes.juliadata.org/stable/man/getting_started/

## Visualisation
http://johnmyleswhite.github.io/Vega.jl/
https://docs.makie.org/stable/
https://beautiful.makie.org/dev/
https://docs.juliaplots.org/latest/

## Statistics
https://juliastats.org/MultivariateStats.jl/dev/pca/
https://juliastats.org/

## Tutorials
https://juliadatascience.io/
https://towardsdatascience.com/read-csv-to-data-frame-in-julia-programming-lang-77f3d0081c14
https://medium.com/coffee-in-a-klein-bottle/visualizing-data-with-julia-using-makie-7685d7850f06
https://towardsdatascience.com/ways-to-detect-and-remove-the-outliers-404d16608dba
<img src="https://miro.medium.com/max/4800/0*FJ9NyCH2r3TZW2Q_.png" width="800"></img>

## Data 
https://www.donneesquebec.ca/recherche/fr/organization/mnbaq

- date acquisition vs date production / genre de l'oeuvre / age artiste / + regression lineaire 
- explorer librairie stat (juliastats)
- analyse factorielle, composante principale (PCA), analyse des correspondances 
- sparql reconciliation nom => genre


### Setup
```julia
using Pkg
Pkg.add("StatsKit")
Pkg.add("DataFrames")
Pkg.add("Vega")
Pkg.add("GLMakie")
Pkg.add("MultivariateStats")
Pkg.add("CSV")
```