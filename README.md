# Enterprise-risk-assessment-dataset
This is the dataset of article “ A large-scale corporation knowledge graph for risk identification in finance corporations ”. The dataset includes the basic information、risk features and labels of 500 companies and their one-hop neighbors as well as two-hop neighbors. The statistic of dataset is shown as the following table:


<table  border="1" >
  <tr ><td colspan="3">Enterprise Atlas</td><td>Counts</td>
	</tr>
  <tr ><td rowspan="2">Nodes </td><td colspan="2">Enterprises</td><td >17814</td>
	</tr>
  <tr ><td colspan="2">Persons</td><td>4567</td>
	</tr>
  <tr ><td rowspan="6">Relationships</td><td rowspan="3">E&E</td><td>Invest_e</td><td>12992</td>
	</tr>
  <tr ><td>Branch</td><td>1720</td> 
	</tr>
  <tr ><td>Own_e</td><td>811</td>
	</tr>
  <tr ><td rowspan="3">P&E</td><td>Serve</td><td>14693</td>
	</tr>
  <tr ><td>Invest_p</td><td>8947</td>
	</tr>
  <tr ><td>Own_p</td><td>7007</td>
  </tr>
</table>

# The format of data file
We provide two kinds of data format, one is the Pandas DataFrame (the example is illustrated in GCN and R-GCN), the other is the dgl graph (the examples are illustrated in the models except GCN and R-GCN).


# How to run the codes
The required packages and corresponding versions are listed in the *requirement.txt*.
For each model, please run  `python train.py` in the command line in the corrseponding file path.
