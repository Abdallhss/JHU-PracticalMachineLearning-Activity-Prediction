This dataset measures different states during a physical activity using on-body sensing to determine if the activity is properly conducted.
From their [website](http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har) we cite the following:

"Six young health participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: exactly according to the specification (Class A), throwing the elbows to the front (Class B), lifting the dumbbell only halfway (Class C), lowering the dumbbell only halfway (Class D) and throwing the hips to the front (Class E)."

After exploring the data, the 159 features were reduced to 52 by droping NA columns, date columns, and low variance columns. 25 features were then extracted using Principal component analysis. Finally, ensemble model of random forest, gradient boosting, linear discriminant analysis, and support vector machines was applied to the data. The validation accuracy was about 97.8%.
