# Sequance_Data_Projects
File_Name: Processing IMDB Data Using RNN.ipynb
	- Preparing the IMDB data
	- Training the model with Embedding and SimpleRNN layers
	- Plotting results
	- Using the LSTM layer in Keras
Conclusion: 
achieve up to 86% validation accuracy. Certainly much better
than the SimpleRNN network—that’s largely because LSTM suffers much less from the
vanishing-gradient problem—and slightly better than the fully connected approach.

File_Name: Temperature_forcasting_problem.ipynb
In this file processing of timeseries dataset recorded at the Weather Station at the Max Planck Institute for Biogeochemistry in Jena, Germany.
	- Inspecting the data of the Jena weather dataset
	- Parsing the data
	- Plotting the temperature timeseries
	- Plotting the first 10 days of the temperature timeseries
	- Normalizing the data
	- Preparing the training, validation, and test generators
	- Computing the common-sense baseline MAE
	- Converting the MAE back to a Celsius error
	- Training and evaluating a densely connected model
	- Training and evaluating a GRU-based model
