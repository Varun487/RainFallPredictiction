# RainFallPredictiction

This notebook tries to answer the question of whether a farmer would need to invest money in irrigation.

The variables we need are `crop`, `month`, `year`, and `region`.

The target variable (our prediction) is simply the avearage amount of rainfall that occurs in the `month`, given historical rainfall data.

We build a simple linear model and perform regression and generate our prediction.

Using this prediction and the `crop` we perform hypothesis testing to see whether or not irrigation will be required to grow the crop.
