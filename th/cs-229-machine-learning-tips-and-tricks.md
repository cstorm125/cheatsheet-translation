**Machine Learning tips and tricks translation** [[webpage]](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-machine-learning-tips-and-tricks)

<br>

**1. Machine Learning tips and tricks cheatsheet**

&#10230;สรุปเคล็ดลับและเทคนิคการทำ machine learning (การเรียนรู้ของเครื่อง)

<br>

**2. Classification metrics**

&#10230;ตัวชี้วัดการจำแนกประเภท (classification metrics)

<br>

**3. In a context of a binary classification, here are the main metrics that are important to track in order to assess the performance of the model.**

&#10230;ในบริบทของการจำแนกประเภทแบบทวิภาค (binary classification) ตัวชี้วัดหลักที่สำคัญสำหรับการประเมินผลโมเดล ได้แก่

<br>

**4. Confusion matrix ― The confusion matrix is used to have a more complete picture when assessing the performance of a model. It is defined as follows:**

&#10230;เมทริกซ์ความสับสน (confusion matrix) - เมทริกซ์ความสับสนใช้สำหรับประเมินผลโมเดล

<br>

**5. [Predicted class, Actual class]**

&#10230;[ประเภทที่ทำนาย, ประเภทจริง] ([predicted class, actual class])

<br>

**6. Main metrics ― The following metrics are commonly used to assess the performance of classification models:**

&#10230;ตัวชี้วัดหลัก ー โดยทั่วไปแล้ว เราจะประเมินประสิทธิผลของโมเดลจำแนกประเภทด้วยตัวชี้วัดต่อไปนี้

<br>

**7. [Metric, Formula, Interpretation]**

&#10230;[ตัวชี้วัด, สมการ, การตีความ]

<br>

**8. Overall performance of model**

&#10230;ประสิทธิผลโดยรวมของโมเดล

<br>

**9. How accurate the positive predictions are**

&#10230;ทำนายผลลัพธ์เชิงบวกแม่นยำแค่ไหน

<br>

**10. Coverage of actual positive sample**

&#10230;ทำนายตัวอย่างผลลัพธ์เชิงบวกจริงได้ครอบคลุมแค่ไหน

<br>

**11. Coverage of actual negative sample**

&#10230;ทำนายตัวอย่างผลลัพธ์เชิงลบจริงได้ครอบคลุมแค่ไหน

<br>

**12. Hybrid metric useful for unbalanced classes**

&#10230;ตัวชี้วัดลูกผสมเหมาะสำหรับกรณีที่จำนวนตัวอย่างในแต่ละประเภทไม่สมดุล (unbalanced class)

<br>

**13. ROC ― The receiver operating curve, also noted ROC, is the plot of TPR versus FPR by varying the threshold. These metrics are are summed up in the table below:**

&#10230;ROC ー เส้นโค้งลักษณะเฉพาะดำเนินการตรวจรับ (receiver operating characteristic curve) หรือเรียกว่า เส้นโค้ง ROC คือกราฟที่แสดงความสัมพันธ์ระหว่างอัตราบวกจริง (true positive rate; TPR) และ อัตราบวกเท็จ (false positive rate; FPR) ในขีดแบ่ง (threshold) การทำนายที่ต่างกัน ตัวชี้วัดเหล่านี้นิยามว่า

<br>

**14. [Metric, Formula, Equivalent]**

&#10230;[ตัวชี้วัด, สมการ, รูปแบบสมมูล]

<br>

**15. AUC ― The area under the receiving operating curve, also noted AUC or AUROC, is the area below the ROC as shown in the following figure:**

&#10230;AUC ー พื้นที่ใต้กราฟ ROC หรือเรียกว่า AUC หรือ AUROC (area under ROC curve) คือพื้นที่ใต้กราฟ ROC ดังรูป

<br>

**16. [Actual, Predicted]**

&#10230;[จริง, ทำนาย]

<br>

**17. Basic metrics ― Given a regression model f, the following metrics are commonly used to assess the performance of the model:**

&#10230;ตัวชี้วัดพื้นฐาน ー ตัวชี้วัดต่อไปนี้ใช้สำหรับประเมินประสิทธิผลของโมเดลการถดถอย (regression) f:

<br>

**18. [Total sum of squares, Explained sum of squares, Residual sum of squares]**

&#10230;[ผลรวมกำลังสองทั้งหมด (total sum of squares; TSS), ผลรวมกำลังสองที่อธิบายได้ (explained sum of squares; ESS), ผลรวมกำลังสองของส่วนเหลือ (residual sum of squares; RSS)]

<br>

**19. Coefficient of determination ― The coefficient of determination, often noted R2 or r2, provides a measure of how well the observed outcomes are replicated by the model and is defined as follows:**

&#10230;สัมประสิทธิ์การกำหนด (coefficient of determination) ー สัมประสิทธิ์การกำหนด มักแทนด้วย R2 หรือ r2 วัดว่าโมเดลทำนายได้ใกล้เคียงกับผลลัพธ์ที่สังเกตได้ (observed outcome) เท่าใด นิยามดังนี้:

<br>

**20. Main metrics ― The following metrics are commonly used to assess the performance of regression models, by taking into account the number of variables n that they take into consideration:**

&#10230;ตัวชี้วัดหลัก ー โดยทั่วไปแล้ว เราจะประเมินประสิทธิผลของโมเดลการถดถอยด้วยตัวชี้วัดต่อไปนี้ โดยให้ n เป็นจำนวนตัวอย่างและ m เป็นจำนวนตัวแปรต้น:

<br>

**21. where L is the likelihood and ˆσ2 is an estimate of the variance associated with each response.**

&#10230;โดย L คือภาวะน่าจะเป็น (likelihood) และ ˆσ2 คือค่าประมาณของความแปรปรวนส่วนเหลือ

<br>

**22. Model selection**

&#10230;การเลือกโมเดล

<br>

**23. Vocabulary ― When selecting a model, we distinguish 3 different parts of the data that we have as follows:**

&#10230;คำศัพท์ - เวลาเราเลือกโมเดล เราจะแบ่งข้อมูลเป็น 3 ส่วน ดังนี้:

<br>

**24. [Training set, Validation set, Testing set]**

&#10230;[ชุดข้อมูลฝึกฝน (training set), ชุดข้อมูลตรวจสอบ (validation set), ชุดข้อมูลทดสอบ (test set)]

<br>

**25. [Model is trained, Model is assessed, Model gives predictions]**

&#10230;[โมเดลถูกฝึกฝน, โมเดลถูกประเมิน, โมเดลให้คำทำนาย]

<br>

**26. [Usually 80% of the dataset, Usually 20% of the dataset]**

&#10230;[มักใช้ 80% ของชุดข้อมูล, มักใช้ 20% ของชุดข้อมูล]

<br>

**27. [Also called hold-out or development set, Unseen data]**

&#10230;[บ้างเรียกว่าชุดข้อมูลที่กันไว้ (hold-out set) หรือชุดข้อมูลสำหรับพัฒนาโมเดล (development set), ข้อมูลที่ไม่เคยเห็น]

<br>

**28. Once the model has been chosen, it is trained on the entire dataset and tested on the unseen test set. These are represented in the figure below:**

&#10230;เมื่อโมเดลถูกเลือก เราจะฝึกฝนมันบนชุดข้อมูลทั้่งหมดและทดสอบบนชุดข้อมูลทดสอบที่มันไม่เคยเห็น ตามรูปด้านล่าง

<br>

**29. Cross-validation ― Cross-validation, also noted CV, is a method that is used to select a model that does not rely too much on the initial training set. The different types are summed up in the table below:**

&#10230;การตรวจสอบไขว้ (cross-validation) - การตรวจสอบไขว้ (cross-validation; CV) คือวิธีการเลือกโมเดลโดยไม่พึ่งพาชุดข้อมูลฝึกฝนเบื้องต้นมากนัก มีหลายวิิธีการดังต่อไปนี้:

<br>

**30. [Training on k−1 folds and assessment on the remaining one, Training on n−p observations and assessment on the p remaining ones]**

&#10230;[ฝึกฝนโมเดลด้วยชุดข้อมูลย่อย k-1 ส่วนและประเมินโมเดลด้วย 1 ส่วนที่เหลือ, ฝึกฝนโมเดลด้วยตัวอย่าง n-p อันและประเมินด้วยตัวอย่าง p อันที่เหลือ]

<br>

**31. [Generally k=5 or 10, Case p=1 is called leave-one-out]**

&#10230;[โดยทั่วไป k=5 หรือ 10, กรณีที่ p=1 เรียกว่า กันไว้หนึ่ง (leave-one-out)]

<br>

**32. The most commonly used method is called k-fold cross-validation and splits the training data into k folds to validate the model on one fold while training the model on the k−1 other folds, all of this k times. The error is then averaged over the k folds and is named cross-validation error.**

&#10230;วิธีการที่นิยมใช้มากที่สุดเรียกว่าการตรวจสอบไขว้แบบ k-ส่วน (k-fold corss-validation) แบ่งชุดข้อมูลฝึกฝนเป็น k ส่วนแล้วฝึกฝนโมเดลด้วยข้อมูล k-1 ส่วนและตรวจสอบโมเดลด้วย 1 ส่วนที่เหลือ ทำวนไป k รอบ ค่าผิดผลาด (error) ของแต่ละส่วนจะถูกนำมาหาค่าเฉลี่ยแล้วเรียกว่า ค่าผิดพลาดการตรวจสอบไขว้ (cross-validation error)

<br>

**33. Regularization ― The regularization procedure aims at avoiding the model to overfit the data and thus deals with high variance issues. The following table sums up the different types of commonly used regularization techniques:**

&#10230;การปรับให้เหมาะสม (regularization) - จุดมุ่งหมายของการปรับให้เหมาะสมคือหลีกเลี่ยงไม่ให้โมเดลจดจำเฉพาะข้อมูลฝึกอบรมมากเกินไป (overfit) และจัดการกับปัญหาความแปรปรวนของคำทำนายสูง ตารางต่อไปนี้สรุปเทคนิคการปรับให้เหมาะสมที่นิยมใช้:

<br>

**34. [Shrinks coefficients to 0, Good for variable selection, Makes coefficients smaller, Tradeoff between variable selection and small coefficients]**

&#10230;[หดค่าสัมประสิทธิ์เป็น 0, เหมาะสำหรับการเลือกตัวแปร, ทำให้ค่าสัมประสิทธิ์เล็กลง, ต้องเลือกระหว่างการเลือกตัวแปรหรือสัมประสิทธิ์เล็กลง]

<br>

**35. Diagnostics**

&#10230;การวินิฉัย (diagnostics)

<br>

**36. Bias ― The bias of a model is the difference between the expected prediction and the correct model that we try to predict for given data points.**

&#10230;ความเอนเอียง (bias) - ความเอนเอียงของโมเดลคือความต่างระหว่างคำทำนายที่คาดหมาย (expected prediction) จากโมเดลของเราและโมเดลที่ถูกต้องที่แท้จริงสำหรับตัวอย่างที่ให้มา

<br>

**37. Variance ― The variance of a model is the variability of the model prediction for given data points.**

&#10230;ความแปรปรวน (variance) - ความแปรปรวนของโมเดลคือความแปรปรวนของคำทำนายของโมเดลสำหรับตัวอย่างที่ให้มา

<br>

**38. Bias/variance tradeoff ― The simpler the model, the higher the bias, and the more complex the model, the higher the variance.**

&#10230;การได้อย่างเสียอย่างของความเอนเอียงและความแปรปรวน (bias/variance tradeoff) - โมเดลยิ่งเรียบง่าย ความเอนเอียงยิ่งสูง โมเดลยิ่งซับซ้อน ความแปรปรวนยิ่งสูง

<br>

**39. [Symptoms, Regression illustration, classification illustration, deep learning illustration, possible remedies]**

&#10230;[อาการ, รูปแสดงโมเดลการถดถอย, รูปแสดงโมเดลจำแนกประเภท, รูปแสดงโมเดลการเรียนรู้เชิงลึก (deep learning), วิธีแก้ไขที่เป็นไปได้]

<br>

**40. [High training error, Training error close to test error, High bias, Training error slightly lower than test error, Very low training error, Training error much lower than test error, High variance]**

&#10230;[ค่าผิดพลาดช่วงฝึกฝน (training error) สูง, ค่าผิดพลาดช่วงฝึกฝนใกล้กับช่วงทดสอบ (test error), ความเอนเอียงสูง, ค่าผิดพลาดช่วงฝึกฝนต่ำกว่าช่วงทดสอบเล็กน้อย, ค่าผิดพลาดช่วงฝึกฝนต่ำมาก, ค่าผิดพลาดช่วงฝึกฝนต่ำกว่าช่วงทดสอบมาก, ความแปรปรวนสูง]

<br>

**41. [Complexify model, Add more features, Train longer, Perform regularization, Get more data]**

&#10230;[ทำโมเดลให้ซับซ้อนขึ้น, เพิ่มตัวแปรต้น, ฝึกฝนให้เยอะขึ้น, ทำการปรับให้เหมาะสม, หาข้อมูลเพิ่ม]

<br>

**42. Error analysis ― Error analysis is analyzing the root cause of the difference in performance between the current and the perfect models.**

&#10230;การวิเคราะห์ข้อผิดพลาด - การวิเคราะห์ข้อผิดพลาดคือการหาสาเหตุต้นตอของความต่างระหว่างประสิทธิผลของโมเดลปัจจุบันและโมเดลที่สมบูรณ์แบบ

<br>

**43. Ablative analysis ― Ablative analysis is analyzing the root cause of the difference in performance between the current and the baseline models.**

&#10230;การวิเคราะห์แบบลดทอน (ablative analysis) - การวิเคราะห์แบบลดทอนคือการวิเคราะห์ถึงสาเหตุต้นตอของโมเดลปัจจุบันและโมเดลตั้งต้น (baseline model)

<br>

**44. Regression metrics**

&#10230;ตัวชี้วัดการถดถอย (regression metrics)

<br>

**45. [Classification metrics, confusion matrix, accuracy, precision, recall, F1 score, ROC]**

&#10230;[ตัวชี้วัดการจำแนกประเภท, เมทริกซ์ความสับสน, ความแม่นยำ, ความเที่ยง (precision), การเรียกคืน (recall), คะแนน F1 (F1 score), ROC]

<br>

**46. [Regression metrics, R squared, Mallow's CP, AIC, BIC]**

&#10230;[ตัวชี้วัดการถดถอย, R squared, Mallow's CP, AIC, BIC]

<br>

**47. [Model selection, cross-validation, regularization]**

&#10230;[การเลือกโมเดล, การตรวจสอบไขว้, การปรับให้เหมาะสม]

<br>

**48. [Diagnostics, Bias/variance tradeoff, error/ablative analysis]**

&#10230;[การวินิจฉัย, การได้อย่างเสียอย่างของความเอนเอียงและความแปรปรวน, การวิเคราะห์ข้อผิดพลาด/แบบลดทอน]
