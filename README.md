# Unsupervised-Learning
Module 17

Resampling:

    While all 3 of the resampling models have a decent recalls, which means that we are appropriately most of the risky loans accordingly, our precision is abysmal. 
    Even though a false positive is much worse than a false negative because the loses from one default greatly outweigh the lose from denying a safe loan, a 2% precision is an order of magnitude off the mark.
    None of these are exciting in their results, but the undersampling seems to have done marginally better than the others with the strongest recall and second strongest accuracy score.

Extention:

    Both of these new models offer a market improvement across the board over the resampling models. 
    The random forest is very impressive not only with boosting all 3 of the precision, recall, and accuracy, but also the feature_importances_ gives a peak at what the model ended up being the strongest predictors. 
    However all of those remarkable features do not quite measure up to EasyEnsemble. 
    EasyEnsemble may not have anything as nifty as feature_importances_ but it more than makes up for it by out performing the random forest. 
    Precision, recall, and accuracy are significantly greater in this final iteration, having the highest recall and accuracy is great but this is the only model that manages to bring the precision out of the single digits and all the way up to 27%. For these reason the EasyEnsemble model is not just the best of the bunch, but is a good model in its own right.