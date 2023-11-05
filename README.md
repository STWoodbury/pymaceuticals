# pymaceuticals
A Data Analysis for Drug Treatments Among Mouse Subjects

The attached analysis at ['pymaceuticals_analysis](pymaceuticals_analysis.ipynb) examines the relationship of various drug treatment regimens to the volume of tumors in experimental mice for treatment periods spanning up to 45 days.

The n of sample mice was 248, with 50.4% Male  The analysis below examines the relationship of various drug treatment regimens to the volume of tumors in experimental mice for treatment periods spanning up to 45 days.

The n of sample mice was 248, with 50.4% Male sample mice, and 49.6% Female sample mice.

The process for analysis was as follows:

1. The sample data was merged into a single dataframe by Mouse ID.
2. Any repeat data was dropped from the dataframe for the remainder of analysis.
3. The mean, median, variance, standard deviation, and standard error was established across each treatment regimen.
4. The sample size of each treatment regimen was established.
5. The quartiles and outliers were calculated and plotted for 4 of the treatment regimens(Capomulin, Ramicane, Infubinol, and Ceftamin).
6. The Capomulin treatment group was isolated and evaluated for two metrics:
    
    A. Tumor size over time (for one random subject)
    
    B. Average tumor size vs. weight of subject (across all in the treatment group)

The following conclusions can be taken from the analysis: 

1. Samples from the Capomulin and Ramicane group show the smallest average tumor volumes of all treatment regimens as well as the smallest final tumor volumes of any of the four selected treatment regimens.

2. Tumor Volume decreases for Capomulin group subjects across time, reaching it's minimum volume on days 30-40 of treatment.

3. Mouse subject weight shows a 70.9% correlation to tumor volumeamong subjects in the Capomulin group.mice, and 49.6% Female sample mice.

The process for analysis was as follows:

1. The sample data was merged into a single dataframe by Mouse ID.
2. Any repeat data was dropped from the dataframe for the remainder of analysis.
3. The mean, median, variance, standard deviation, and standard error was established across each treatment regimen.
4. The sample size of each treatment regimen was established.
5. The quartiles and outliers were calculated and plotted for 4 of the treatment regimens(Capomulin, Ramicane, Infubinol, and Ceftamin).
6. The Capomulin treatment group was isolated and evaluated for two metrics:
    
    A. Tumor size over time (for one random subject)
    
    B. Average tumor size vs. weight of subject (across all in the treatment group)

The following conclusions can be taken from the analysis: 

1. Samples from the Capomulin and Ramicane group show the smallest average tumor volumes of all treatment regimens as well as the smallest final tumor volumes of any of the four selected treatment regimens.

2. Tumor Volume decreases for Capomulin group subjects across time, reaching it's minimum volume on days 30-40 of treatment.

3. Mouse subject weight shows a 70.9% correlation to tumor volumeamong subjects in the Capomulin group.