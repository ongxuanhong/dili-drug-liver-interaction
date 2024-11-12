# dili-drug-liver-interaction

## Padel descriptor
Ref: http://www.yapcwsoft.com/dd/padeldescriptor/

java -jar PaDEL-Descriptor.jar -help
java -jar PaDEL-Descriptor.jar -threads 12  -fingerprints -dir data/ -file data/Training_Group_PaDel_x20.csv
java -jar PaDEL-Descriptor.jar -threads 4  -fingerprints -dir data_test/ -file data_test/Testing_Group_PaDel_x20.csv