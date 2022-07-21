# Predicting Silicon (impurities) concentration in refined iron concentrate obtained from purifying iron ore

# Steps involved -

### Preprocessing -
<p> 7 coulmns in dataset for 'Floatation Column Air Flow' and 'Floatation Column Level'. Mean and median of 'Floatation Column Air Flow' and 'Floatation Column Level' found, thereby dereasing the number of features to be used while training</p>

### Analysis - 

Features used - 
<ul>
    <li>%Iron in impure iron ore (to be purified)
    <li>%Silica in impure iron ore
    <li>Starch Flow
    <li>Amina Flow
    <li>Ore pulp Flow
    <li>Ore pulp pH
    <li>Ore pulp density
    <li>Floatation Column Air Flow Mean
    <li>Floatation Column Air Flow Median
    <li>Floatation Column Level Mean
    <li>Floatation Column Level Median
</ul>

Models used - 
<ul>
    <li>XGB (ML model) - Accuracy obtained:0.0898 (mean absolute errror)
    <li>LSTM layers (neural network) - Accuracy obtained:0.135 (mean absolute errror)
    <li>SimpleRNN layers (neural network) - Accuracy obtained:0.133 (mean absolute errror)
</ul>
