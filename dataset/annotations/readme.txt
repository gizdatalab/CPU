this dir contains the annotations performed on argilla
1. checkspans_annotated: This is done to assess the quality of Dataset especially wrt to mapping of ResponseText to Paragraph(holdoutdata is used for same)
2. subtarget_annotated: This is done to get the Netzero, GHGLabel and nonGHGLabel data ready for multilabel setting.
3. holdoutdata_annotated: This dataset which is not in policy-classifcation published dataset is kept separate to run few quick analysis like including: 
  Annotator Agreement
  Model Assessment on human annotated/verified labels etc
