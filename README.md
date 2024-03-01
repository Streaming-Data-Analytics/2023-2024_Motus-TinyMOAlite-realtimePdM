# Real Time Predictive Maintenance task using a Quantized MOA Version on a Microprocessor

============

Optional project of the [Streaming Data Analytics](http://emanueledellavalle.org/teaching/streaming-data-analytics-2023-24/) course provided by [Politecnico di Milano]

Student: **[To be assigned]**

The project will use the Java library tinyMOA-lite1 on a Raspberry Pi simulator to solve a live classification task. The aim is to train several models on tinyMOA-lite on a Raspberry Pi simulator and to show the prediction results on a dashboard in real-time.

More in practice, for the AI4I 2020 Predictive Maintenance Dataset2, you have to train and test the Naïve Bayes, KNN, HT, HAT, ARF, Online Bagging, Leveraging Bagging, ARF, and SRP models in tinyMOA-lite on a Raspberry Pi simulator one sample at a time, showing in real-time in a dashboard the features in input, the prediction, and the metrics results achieved.
About the data ingestion to the Raspberry Pi, it is expected to send one sample at a time to the device and retrieve the prediction. It does not matter if the process will be slower.

You should use the following metrics to compare the results: Accuracy, Balanced Accuracy, Geometric Mean, and CohenKappa

Moreover, you should keep track of the Time, CPU and RAM usage to test and train the models. The project must also include some plots to better show the results.

You are required to create a .sh or .java file with the code for testing the models in tinyMOA-lite and the code to replicate the dashboard (you can choose the language you prefer). You must include comments for the principal instructions, and you are allowed to import external py modules. Additionally, ensure you thoroughly comment on the comparison results using various plots associated with the different metrics. Finally, in an external file, briefly discuss the conclusions that can be drawn from the experiment.

We will give you the tinyMOA-lite code after signing an NDA disclosure.

## Note for Students

* Clone the created repository offline;
* Add your name and surname into the Readme file;
* Make any changes to your repository, according to the specific assignment;
* Add a `requirement.txt` file for code reproducibility and instructions on how to replicate the results;
* Add an open-source license, e.g., Apache 2.0;
* Commit your changes to your local repository;
* Push your changes to your online repository.
