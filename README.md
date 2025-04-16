# ML-running-thesis

NEW ASSIGNED STUFF COMPLETED :

SMOTE ❌ -> only for classification

STRATIFIED K-FOLD ❌ -> only for classification

K-FOLD FOR TREE  ✅

LINEAR REGRESSION FOR CALORIES DATASET ✅

K-FOLD FOR LINEAR ✅

K-FOLD FOR MULTIOUTPUT ✅

HISTOGRAM FOR CALORIES = CALORIES ✅

HISTOGRAMS FOR LINEAR REGRESSION ✅

USE VALIDATION -70-10-20 --LATER ✅

REMOVE MAPE ✅

CHANGE GRID SEARCH WITH VALIDATION ✅

IMPLEMENTED A LEAVE ONE OUT TO CHECK SINGULR ERROR EVERY TIME ✅

TESTED MODEL ON TEST DATA ✅


NEW COMMENTS FOR VALENTINA:

- K-fold for linear brings r2 of vo2max positive 
- K-fold for linear brings r2 of days and weekly is close to 0 for folds=5

-Kfold for multioutput tree (ll 3 models) all have a very bad r2...

- Histograms for Caloris exemplifies the correct behaviour
- Histograms for linear regression done

- Using validation set everywhere for multioutputtrees
- GridSearch now uses validation set

- Removed  mape and single mape

- Tested the model onto real data 


OVERALL COMMENTS :

    - K fold was able to pump up r2 in linear regression for weeklykm,days and vo2max
    - K fold is negative for all the Multioutpout trees (I wanna cry)
    - Everything is checked on validation, but not in linear Regression should I do it also in linear regression?
    - Histograms for linear regression show that linear regression works as expected
    - MODEL ACTUALLY PERFORM ON UNSEEN DATA!!

    - You can check all in relative section both in multioutputtrees and linearregression jupyters (name are very intuitive soyou should be able to understand under which sections everything is placed)

    - Thankss in advance!!






**OLD**


OLD PER VALENTINA AND TO KEEP TRACK OF WHAT HAS BEEN DONE

THIS IS WHAT HAS BEEN SAID AT THE MEETING (did it all):

- / CHECK mape and other metrics of evluation ✅:
    
    - Added MAPE, ROOT MSE 

- change seeds and compare performance 

- Linear regression - Interaction checks ✅
    
    - Predictors : x qui
    - Y - one at a time, (check if possible multiple)

- Check for other datasets.✅

- Explain everything, feure extraction, r2,and metrics. ✅

- I am not using validation, just remember.✅



OLD COMMENTS FOR VALENTINA :

__HIGHLY RECOMMENDED: don't run the code (multioutputTrees.ipynb) because I have some hardcoded parameters to manage new stuff that would break the old. Just look at it already ran. THANKSS, sorry for this__

- Added MAPE and ROOT MSE, it can be seen in section 'REQUESTED BY VALENTINA' in multioputputTrees.ipynb 

    * Main considerations : MAPE < 20% is good and it is like that for  weight,days and vo2max. WeeklyKm has a very high MAPE

- Linear Regression analsysis, it can be seen in linearRegression.ipynb :
    
    * Showed that we are correct in choosing weight,days,weeklyKM and vo2max as main indicators for a better marthon time
    * Unlikely our X space : marathon_time_in_minutes, height, age, yearsTrained seems not to be able to recognise patterns for the above relization except for weight because it has a very nice relation with height. (I AM ALWAYS TALKING ABOUT UNSEEN DATA HERE)

- Other datasets anlysis can be seen in section 'CALORIES DATASET' in multiOutputTrees.ipynb:

    * This proves that model works correctly !! because we get a 96% R2 for the CaloriesBurn prediction. (Average speed was just placed because it should be multioutput)
    * The other try with another dataset is wrong because there are too many dependencies.

- MAIL REQUEST --> keep same metrics and change marathon time can be found in section 'USER TRIALS WITH HISTOGRAM' win multioutputTrees.ipynb:

    * The pattern of increase or decrease of the variables is there so model effectively works!!


__I was not being exhaustive because I would like to explain everything in the meeting becuse it's hard to explain everything writing here__ 



