# ML-running-thesis

PER VALENTINA AND TO KEEP TRACK OF WHAT HAS BEEN DONE

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


COMMENTS FOR VALENTINA :

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



