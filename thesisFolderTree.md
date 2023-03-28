# The impact of residual strains on the stress analysis of atherosclerotic carotid vessels predictions based on the homogenous stress hypothesis
## Master Thesis
### Biomedical Engineering - University of Rome Tor Vergata

# Folders tree:

```mermaid
gitGraph
	commit id:"Test01"
	commit id:"Test02"
	branch Test
	commit id:"Test03" tag:"conversion into STL"
	branch SingleFile
	commit id: "single_file_v1" tag:"Full single file reading code" type: HIGHLIGHT
	merge Test
	checkout Test
	commit id:"fluid.mph" type:REVERSE
	commit id:"Test04" tag: "loop for metrics"
	merge SingleFile
	branch ParametersTest
	commit id:"parameter_test_v1"
	checkout Test
	commit id:"Test05" tag: "fake wall"
	branch ComsolGrowth
	commit id:"Test06" tag: "test"
	commit id:"Test07" tag: "law"
	commit id:"Test08" tag: "cylinder"
	checkout Test
	commit id:"Test09" tag:"read data"
	commit id:"Test10"
	branch Analysis
	commit id:"643"
	commit id:"753"
	commit id:"710"
	commit id:"779"
	checkout ComsolGrowth
	commit id:"Test11"
	commit id:"Test12" tag:"cyl growth"
	commit id:"Test13" tag:"v2"
	commit id:"Test15" tag:"stats"
	checkout Test
	commit id:"Test14" tag:"growth carotid"
	branch RealGrowth
	commit id:"643_growth"
	checkout Test
	commit id:"Test16" tag:"growth"
	branch SP1
	commit id:"643_sp1"
	commit id:"710_sp1"
	checkout Test
	commit id:"Test17" tag:"res. strain"
	branch ResidualStrain
	commit id:"643_res"
	commit id:"710_res"
	checkout Test
	commit id:"Test18" tag:"free upper BCs"
	branch FreeUpperBoundary
	commit id:"643_Test18"
	checkout Test
	commit id:"Test19" tag:"final test"
	branch FinalTest
	commit id:"cyl"
	commit id:"643_test_final"
	merge Test
	commit id:"Test20" tag:"mesh refine"
	branch Final
	commit id:"643_final"
	checkout Test
	commit id:"Test21"
	branch NewFormulation
	commit id:"Test22"
	commit id:"643_final_growth" tag: "completed"
	checkout Test
	branch ConvergenceAnalysisFinal
	commit id:"Test23" tag: "ok"
	checkout Test
	commit id:"Test24" tag: "graphs and comparison"
```
