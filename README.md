# bixi_demand_analysis
Analysis of the demand for BIXI bikes and its future prediction

BIXI is a bicycle sharing system operational in Montreal, Canada since 2009. Users can rent bikes at bike docking stations for short commutes in the city. It is a convenient way to ride bikes as users can rent a bike from a station, ride up to their destination and drop off the bike at the nearest docking station. There is a usage fee based on the duration of the trip and there are options in the form of monthly & seasonal memberships as well.

The data science problem discussed here is about predicting the demand for BIXI bikes on any given hour of the day. The problem was a business case to be solved as part of the course 'Data Science for Business Decisions' offered by McGill University, Montreal.

The data used for the analysis was generated in the year 2018 & is available for download from the website of BIXI. It is believed that week-days & weekends have two distinct demand patterns and weather is also a factor that affects demand. The weather data for the analysis was obtained from the Government of Canada website and it is assumed that the whole of Montreal have the same weather condition as what was observed at McTavish reservoir station, which is near the McGill University.

There are two objectives for this data science project. Firstly, visualization of the demand patterns on week-days & week-ends which is accomplished using Tableau. Secondly, to build a predictive model that allows BIXI to predict the demand of bikes by hour of the day. This is achieved using Alteryx.

The attached Tableau packaged workbooks were used for analysis & visualizations and Alteryx workflow was used for the predictive modelling.
The 4 zipped files "OD_2018-merged-3-0?.zip" need to be unzipped and merged sequentially to form "OD_2018-merged-3.csv". The merged csv file should be fed to the Tableau & Alteryx workflows.
