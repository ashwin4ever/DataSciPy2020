# Course : Neural Data Science with Python 

![Logo](miscFiles/course-logo.png "Course Logo")


### End-of-Course projects 

Your work on the **End-of-Course Project** will make up 50 % of your final course mark. 

One or teams of maximal two students can choose a project from the list below. 
The evaluation will be based on a written report (not more than **3 pages**) and a presentation of the results in front of a jury. The **project submission deadline is January the 3rd, 2021 (24h)**. And the **project presentations** 
will take place on **Thursday January 7th, 2021 from 9h30 through 12h30**. 
Each presentation is limited to 10 min followed by 5 min of questions. 

The evaluation jury is composed of Jonas Ranft, Karine Audouze, Marcel Stimberg and Michael Graupner. 

The report and talk can be prepared in English or French, up to the choice of the student. 

### Practial tips on the End-of-Course projects 

Find the slides from the presentation of the projects with practial tips [here](lectures/End-of-Course-Projects.pdf). You can 
furthermore download the report template in [Word format (docx)](miscFiles/summary_end-of-course-project_template.docx) or 
[LibreOffice format (odt)](miscFiles/summary_end-of-course-project_template.odt). 

### Available projects


--------

<table>
<tr>
<th> # </th>
<th> Title </th>
<th>Description</th>
<th>Techniques/skills involvedd</th>
<th>Contact person</th>
</tr>
<!--- ======================== -->
<tr>
<td valign="top">1</td>
<td valign="top"> <b>Testing classifier performance on hand-written digits</b></td>
<td valign="top"> Use the <a href="http://yann.lecun.com/exdb/mnist/">MNIST database</a> of handwritten digits from 0 through 9 and test the performance of different classifiers on how well they can learn to identify individual digits. The dataset has a training set of 60,000 examples, and a test set of 10,000 examples. The digits have been size-normalized and centered in a fixed-size image.

The images from the training dataset would be the input for the classifier and the know identity of the digit would be used to train the classfier. The performance of the classifier is then tested on the test set of images which have never been shown to the classifier. Compare the error rate (the fraction of test dataset images which were not correctly classified) for SVM classifier with different kernel functions (linear, polynomial). 
</td>
<td valign="top">implementing different classifiers and testing performance : SVM with different kernels (linear and nonlinear); reading and treating image data</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>
<!--- ======================== -->
<tr>
<td valign="top">2</td>
<td valign="top"> <b>Exploring existence of clusters in hand-written digits</b></td>
<td valign="top"> Use the <a href="http://yann.lecun.com/exdb/mnist/">MNIST database</a> of handwritten digits from 0 through 9 and explore the existence and number of distinct clusters in that dataset. Use the k-means clustering algorithm with different number of pre-determined clusters to find. Evalute the separation between the found clusters using the Silhouette analysis. Use both together, the training set 60,000 examples, and a test set of 10,000 examples. The digits have been size-normalized and centered in a fixed-size image.

The images from the training dataset would be the input for the clustering algorithm. The know identity of the digit can be used to verify whether clusters found corespond to a specific digit. Which digits fall into indistinguishable clusters?   
</td>
<td valign="top">implementing k-means clustering; testing cluster separation with Silhouette analysis; reading and treating image data</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>
<!--- ======================== -->
<tr>
<td valign="top">3</td>
<td valign="top"> <b>Extracting and analyzing spike-times from membrane potential recording</b></td>
<td valign="top">Extract spike times from an electrophysiological recordings and characterize spiking statistics. You are provided with whole-cell recordings from medium spiny neurons in the striatum which received pre-synaptic inputs and current injections. The direct current injection elicited action potenials in the recorded neurons. The aim is to extract the times of the presynaptic stimulation - from the stimulus artifact - and the times of the postsynaptic action potentials. Firing rates, the coefficient of variation and the time difference between the pre-synaptic stimulation and the postsynaptic action potentials are to be calculated. 
</td>
<td valign="top">event extraction through thresholding of a time series; calculating spiking statistics such as firing rate, CV, spike-time differences</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">4</td>
<td valign="top"> <b>Analyze spectral content in an LFP recording</b></td>
<td valign="top">Compute the frequency concent in a local field potential (LFP) recording from the prefrontal cortex during a fear conditioning trial. Animal were presented with a tone as conditioned stimulus which predicted a unconditioned stimulus (US) - light foot shock - applied after a fixed time delay. We know that the spectral content of the LFP signal changes in response to the tone and in anticipation of the unconditioned stimulus. 
The aim of this project is to extrat the spectral information from the LFP recordings as a function of time to investigate the tone evoked changes and the changes linked to the US presentation. 
</td>
<td valign="top">spectral analysis of a LFP time series; perform FFT on parts of the signal; generate spectorgram</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">5</td>
<td valign="top"> <b>Compute tuning curves of monkey visual cortex neurons</b></td>
<td valign="top">Visual cortex single-unit activity was recorded in awake macaque monkeys actively fixating. The visual stimulation consisted of random dot kinematograms which moved in a different direction for each 500 ms stimulus presentation. The recorded neurons in area MT are directional tuned. The task would be to calculate the peri-stimulus time histogram for each stimulus and determine the directional tuning curve of each recorded neuron.
</td>
<td valign="top">spike train handling; PSTH and tuning curve calculation; calculating spiking statistics such as firing rate</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">6</td>
<td valign="top"> <b>Extract local field potential and spikes from extracellular recording in the hippocampus</b></td>
<td valign="top">You are provided with a raw extracellular recording from the hippocampus of a awake behaving rat. The trace has been recorded with a silicone probe and contains the local field potential (LFP) as well as spiking signals. Since both occur at different frequencies, it is possible to separate them through appropriate signal filtering. Your task is to extract the LFP and the spikes from the raw trace further analyze both information. Extract the spectral information as a function of time from the LFP and the instantaneous firing rate, as well as average firing rate and CV from the spikes.  
</td>
<td valign="top">time series analysis; signal filtering; spectral analysis</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>


<!--- ======================== -->
<tr>
<td valign="top">7</td>
<td valign="top"> <b>Leaky-Integrate-and-Fire model with refractory period</b></td>
<td valign="top">In this project, you will implement a numerical simulation of the Leaky-Integrate-and-Fire (LIF) neuron model with refractory period, i.e., for which after each spike the membrane potential is frozen for a short period of time during which inputs are not integrated. This refractory period represents roughly the duration of the action potential in real neurons. You will use the Euler method to solve numerically the subthreshold voltage dynamics in the presence of random, fluctuating inputs, and combine this with a threshold detection mechanism to identify spike times and implement the reset. For a fixed choice of input resistance, threshold and reset potential, you will plot the firing rate as a function of the remaining parameters: (i) the mean and (ii) the standard deviation of the input current, and (iii) the duration of the refractory period.
</td>
<td valign="top">simulation of a single neuron model; noise term; numerical integration; spike train analysis</td>
<td valign="top"><a href="mailto:jonas.ranft@ens.fr">Jonas Ranft</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">8</td>
<td valign="top"> <b>Exponential-Integrate-and-Fire model</b></td>
<td valign="top">The Exponential-Integrate-and-Fire (EIF) neuron model is a slight modification of the classical Leaky-Integrate-and-Fire (LIF) model. Compared to the LIF, the EIF contains an additional, active current that grows exponentially with the potential, characterized by two parameters: a threshold value and the sharpness of the spike onset. This current represents the action-potential-initiating sodium current without explicitly modelling the ion channel dynamics (i.e., no additional variable is introduced). In the EIF, a spike occurs when the potential diverges, which in practice is implemented by comparing the voltage to a large finite value. You will use the Euler method to solve numerically the voltage dynamics in the presence of random, fluctuating inputs, and combine this with a threshold detection mechanism to identify spike times and implement the reset. For a fixed choice of input resistance, threshold parameter and reset potential, you will plot the firing rate as a function of the remaining parameters: (i) the mean and (ii) the standard deviation of the input current, and (iii) the sharpness of the spike onset.
</td>
<td valign="top">simulation of a single neuron model; numerical integration; spike train analysis</td>
<td valign="top"><a href="mailto:jonas.ranft@ens.fr">Jonas Ranft</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">9</td>
<td valign="top"> <b>Dynamics of a network of spiking neurons</b></td>
<td valign="top">Implement a network of recurrently connected leaky-integrate-and-fire neurons using the Brian simulator. The network should match "Model B" from Brunel, J Comp Neurosci (2000), e.g. in its parametrization used in Fig. 2A. Verify that your networks exhibits the expected dynamics in the different regimes (SR, AI, SI fast osc., SI slow osc.) and plot the activity for representative parametrizations of each regime (e.g. like in Fig. 8). For further information, consider reading the description of the "Brunel network" in chapter 13.4 of the "Neuronal Dynamics" textbook by Gerstner et al. (available online: https://neuronaldynamics.epfl.ch/) – note that you can ignore the analytical investigation (Fokker-Planck equations, etc.), both in that chapter and in the original paper.
</td>
<td valign="top">simulation of a spiking neural network; Brian simulator</td>
<td valign="top"><a href="mailto:marcel.stimberg@inserm.fr">Marcel Stimberg</a></td>
</tr>


<!--- ======================== -->
<tr>
<td valign="top">10</td>
<td valign="top"> <b>Coupled oscillators</b></td>
<td valign="top">Implement a simple "network" of two leaky-integrate-and-fire neuron. Each of the neurons should receive a constant input current that makes it spike regularly. Connect the two neurons via a simple synapse (i.e. the first neuron connects to the second, and the second neuron connects to the first). If you start the two neurons with different initial values of their membrane potentials, what behaviour do you see if the two neurons are 1) unconnected, 2) connected with excitatory synapses 3) connected with inhibitory synapses? Neurons of this type are often analysed as "oscillators" that are described by a frequency and a phase. See how this can help you describe the behaviour of the two neurons in the 3 situations considered above.
</td>
<td valign="top">simulation of a simple 2-neuron spiking neural network; Brian simulator</td>
<td valign="top"><a href="mailto:marcel.stimberg@inserm.fr">Marcel Stimberg</a></td>
</tr>
 
<!--- ======================== -->
<tr>
<td valign="top">11</td>
<td valign="top"> <b>Simulate spike propagation in an axon</b></td>
<td valign="top">Use the Brian simulator to build a model of the spike propagation in the giant axon of the squid, reproducing Hodgkin & Huxley's famous experiments. Base your model on the "hh_with_spikes" example in the Brian documentation. First, clearly visualize the propagation in space (e.g. like the visualization in the "hodgkin_huxley_1952" example). Explain (using visualizations) why the spike propagates along the axon in a unidirectional way, i.e. why doesn't it "go back" as well? Then, read about the Q10 temperature coefficient and its effect in the Hodgkin-Huxley model. Simulate and visualize the spike propagation at different temperatures.
</td>
<td valign="top">simulation of a (multi-compartment) Hodgkin-Huxley model; Brian simulator</td>
<td valign="top"><a href="mailto:marcel.stimberg@inserm.fr">Marcel Stimberg</a></td>
</tr>


<!--- ======================== -->
<tr>
<td valign="top">12</td>
<td valign="top"> <b>Endocrine disruptors and metabolic disorders</b></td>
<td valign="top">The aim of this mini-project is to explore the current literature available for a list of compounds known or suspected to be endocrine disruptors, and links them to disorders related to the metabolic systems (obesity, diabetes), the immune systems (and COVID-19), the neurological systems and the reproductive systems. Endocrine disruptors are small molecules to which human are exposed via different sources such as food, medication, environment etc. These compounds may mimic the hormones, and therefore perturb biological mechanisms in our bodies. From the list of 10 compounds (bisphenol A = BPA, bisphenol S = BPS, bisphenol F = BPF, Di(2-ethylhexyl) phthalate = DEHP, dibutyl phthalate = DBP, Perfluorooctanesulfonic acid = PFOS, Perfluorooctanoic acid = PFOA, cadmium = CdCl2, Dichlorodiphenyldichloroethylene = DDE, butyl-paraben), you will perform an automatic literature search using the PubMed database, in order to determine the number of articles related to these compounds, their publication dates, the journal where there are published, etc… and to which metabolic diseases they are linked too. You can also check in the PubChem database for synonyms of the chemical names. Your results will be visualized with graphs that include legends and title. 
</td>
<td valign="top">literature searches, visualization of data</td>
<td valign="top"><a href="mailto:karine.audouze@parisdescartes.fr">Karine Audouze</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">13</td>
<td valign="top"> <b>Evaluation of health risks from PFAS exposure</b></td>
<td valign="top">The aim of this mini-project is to explore the current literature available for the list of known PFAS compounds, and links them to disorders related to the metabolic systems (obesity, diabetes), the immune systems (and COVID-19), the neurological systems and the reproductive systems. Many PFAS compounds exist, and some start to be used as replacement of the 'original' ones, as an alternative solution, but they might be also toxic. From the list of 12 compounds (see below), you will perform an automatic literature search using the PubMed database, in order to determine the number of articles related to these compounds, their publication dates, the journal where there are published, etc… and to which diseases they are linked too. Be careful, for some you may not fond any information (this is possible if the compound has not been studied yet). You can also check in the PubChem database for synonyms of the chemical names. Your results will be visualized with graphs that include legends and title. the 12 compounds are : <br>
Perfluoro-n-butanoic acid<br>
Perfluoro-n-decanoic acid<br>
Perfluorododecanoic acid<br>
Perfluoroheptanoic acid<br>
Perfluorohexanoic acid<br>
Perfluorononanoic acid<br>
perfluorooctane sulfonate<br>
Perfluorooctane sulfonic acid<br>
Perfluorooctanesulfonamide<br>
Perfluorooctanoic acid<br>
Perfluoropentanoic acid<br>
Perfluorotetradecanoic acid<br>
</td>
<td valign="top">literature searches, visualization of data</td>
<td valign="top"><a href="mailto:karine.audouze@parisdescartes.fr">Karine Audouze</a></td>
</tr>


</table>



