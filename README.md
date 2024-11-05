PRAMS dataset downloaded from CDC SAMS server
NCFRP dataset requires a contract and sponsor institution to be accessed.
The NCFRP dataset is a case-only series, thus collecting a control sample from the PRAMS dataset will be crucial to have matched controls

controls specifications:
match:
  - birthweight, sex, gestational age, race
  - create a population distribution of age of death from NCFRP dataset, then randomly assign to samples from the PRAMS controls (alive)
