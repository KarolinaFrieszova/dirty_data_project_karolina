# Decathlon Data

### Description
The data used refer to athletes' performance during two sport events.

### Format
A cleaned data frame has 41 rows and 14 columns:

* The first column represents athletes' names. 
* Following ten columns corresponds to the time perfomance of athletes for ten events of the decathlon. 
* The columns 12 and 13 represent the ranking and the points obtained. 
* The last column is categorical variable corresponding to two sport competitions (Olympic Games and Decastar).

### Source

The Decathlon data comes from _FactoMineR_ package.

* library(FactoMineR)
* data(decathlon)

### Table
| athlete     | sprint_100m | long_jump | shot_put | high_jump | sprint_400m | hurdle_110m | discus | pole_vault | javeline | distance_1500m | rank | points | competition   |
|-------------|-------------|-----------|----------|-----------|-------------|-------------|--------|------------|----------|----------------|------|--------|---------------|
| Sebrle      | 11.04       | 7.58      | 14.83    | 2.07      | 49.81       | 14.69       | 43.75  | 5.02       | 63.19    | 291.7          | 1    | 8217   | Decastar      |
| Clay        | 10.76       | 7.4       | 14.26    | 1.86      | 49.37       | 14.05       | 50.72  | 4.92       | 60.15    | 301.5          | 2    | 8122   | Decastar      |
| Karpov      | 11.02       | 7.3       | 14.77    | 2.04      | 48.37       | 14.09       | 48.95  | 4.92       | 50.31    | 300.2          | 3    | 8099   | Decastar      |
| Bernard     | 11.02       | 7.23      | 14.25    | 1.92      | 48.93       | 14.99       | 40.87  | 5.32       | 62.77    | 280.1          | 4    | 8067   | Decastar      |
| Yurkov      | 11.34       | 7.09      | 15.19    | 2.1       | 50.42       | 15.31       | 46.26  | 4.72       | 63.44    | 276.4          | 5    | 8036   | Decastar      |
| Warners     | 11.11       | 7.6       | 14.31    | 1.98      | 48.68       | 14.23       | 41.1   | 4.92       | 51.77    | 278.1          | 6    | 8030   | Decastar      |
| Zsivoczky   | 11.13       | 7.3       | 13.48    | 2.01      | 48.62       | 14.17       | 45.67  | 4.42       | 55.37    | 268            | 7    | 8004   | Decastar      |
| McMullen    | 10.83       | 7.31      | 13.76    | 2.13      | 49.91       | 14.38       | 44.41  | 4.42       | 56.37    | 285.1          | 8    | 7995   | Decastar      |
| Martineau   | 11.64       | 6.81      | 14.57    | 1.95      | 50.14       | 14.93       | 47.6   | 4.92       | 52.33    | 262.1          | 9    | 7802   | Decastar      |
| Hernu       | 11.37       | 7.56      | 14.41    | 1.86      | 51.1        | 15.06       | 44.99  | 4.82       | 57.19    | 285.1          | 10   | 7733   | Decastar      |
| Barras      | 11.33       | 6.97      | 14.09    | 1.95      | 49.48       | 14.48       | 42.1   | 4.72       | 55.4     | 282            | 11   | 7708   | Decastar      |
| Nool        | 11.33       | 7.27      | 12.68    | 1.98      | 49.2        | 15.29       | 37.92  | 4.62       | 57.44    | 266.6          | 12   | 7651   | Decastar      |
| Bourguignon | 11.36       | 6.8       | 13.46    | 1.86      | 51.16       | 15.67       | 40.49  | 5.02       | 54.68    | 291.7          | 13   | 7313   | Decastar      |
| Sebrle      | 10.85       | 7.84      | 16.36    | 2.12      | 48.36       | 14.05       | 48.72  | 5          | 70.52    | 280.01         | 1    | 8893   | Olympic_Games |
| Clay        | 10.44       | 7.96      | 15.23    | 2.06      | 49.19       | 14.13       | 50.11  | 4.9        | 69.71    | 282            | 2    | 8820   | Olympic_Games |
| Karpov      | 10.5        | 7.81      | 15.93    | 2.09      | 46.81       | 13.97       | 51.65  | 4.6        | 55.54    | 278.11         | 3    | 8725   | Olympic_Games |
| Macey       | 10.89       | 7.47      | 15.73    | 2.15      | 48.97       | 14.56       | 48.34  | 4.4        | 58.46    | 265.42         | 4    | 8414   | Olympic_Games |
| Warners     | 10.62       | 7.74      | 14.48    | 1.97      | 47.97       | 14.01       | 43.73  | 4.9        | 55.39    | 278.05         | 5    | 8343   | Olympic_Games |
| Zsivoczky   | 10.91       | 7.14      | 15.31    | 2.12      | 49.4        | 14.95       | 45.62  | 4.7        | 63.45    | 269.54         | 6    | 8287   | Olympic_Games |
| Hernu       | 10.97       | 7.19      | 14.65    | 2.03      | 48.73       | 14.25       | 44.72  | 4.8        | 57.76    | 264.35         | 7    | 8237   | Olympic_Games |
| Nool        | 10.8        | 7.53      | 14.26    | 1.88      | 48.81       | 14.8        | 42.05  | 5.4        | 61.33    | 276.33         | 8    | 8235   | Olympic_Games |
| Bernard     | 10.69       | 7.48      | 14.8     | 2.12      | 49.13       | 14.17       | 44.75  | 4.4        | 55.27    | 276.31         | 9    | 8225   | Olympic_Games |
| Schwarzl    | 10.98       | 7.49      | 14.01    | 1.94      | 49.76       | 14.25       | 42.43  | 5.1        | 56.32    | 273.56         | 10   | 8102   | Olympic_Games |
| Pogorelov   | 10.95       | 7.31      | 15.1     | 2.06      | 50.79       | 14.21       | 44.6   | 5          | 53.45    | 287.63         | 11   | 8084   | Olympic_Games |
| Schoenbeck  | 10.9        | 7.3       | 14.77    | 1.88      | 50.3        | 14.34       | 44.41  | 5          | 60.89    | 278.82         | 12   | 8077   | Olympic_Games |
| Barras      | 11.14       | 6.99      | 14.91    | 1.94      | 49.41       | 14.37       | 44.83  | 4.6        | 64.55    | 267.09         | 13   | 8067   | Olympic_Games |
| Smith       | 10.85       | 6.81      | 15.24    | 1.91      | 49.27       | 14.01       | 49.02  | 4.2        | 61.52    | 272.74         | 14   | 8023   | Olympic_Games |
| Averyanov   | 10.55       | 7.34      | 14.44    | 1.94      | 49.72       | 14.39       | 39.88  | 4.8        | 54.51    | 271.02         | 15   | 8021   | Olympic_Games |
| Ojaniemi    | 10.68       | 7.5       | 14.97    | 1.94      | 49.12       | 15.01       | 40.35  | 4.6        | 59.26    | 275.71         | 16   | 8006   | Olympic_Games |
| Smirnov     | 10.89       | 7.07      | 13.88    | 1.94      | 49.11       | 14.77       | 42.47  | 4.7        | 60.88    | 263.31         | 17   | 7993   | Olympic_Games |
| Qi          | 11.06       | 7.34      | 13.55    | 1.97      | 49.65       | 14.78       | 45.13  | 4.5        | 60.79    | 272.63         | 18   | 7934   | Olympic_Games |
| Drews       | 10.87       | 7.38      | 13.07    | 1.88      | 48.51       | 14.01       | 40.11  | 5          | 51.53    | 274.21         | 19   | 7926   | Olympic_Games |
| Parkhomenko | 11.14       | 6.61      | 15.69    | 2.03      | 51.04       | 14.88       | 41.9   | 4.8        | 65.82    | 277.94         | 20   | 7918   | Olympic_Games |
| Terek       | 10.92       | 6.94      | 15.15    | 1.94      | 49.56       | 15.12       | 45.62  | 5.3        | 50.62    | 290.36         | 21   | 7893   | Olympic_Games |
| Gomez       | 11.08       | 7.26      | 14.57    | 1.85      | 48.61       | 14.41       | 40.95  | 4.4        | 60.71    | 269.7          | 22   | 7865   | Olympic_Games |
| Turi        | 11.08       | 6.91      | 13.62    | 2.03      | 51.67       | 14.26       | 39.83  | 4.8        | 59.34    | 290.01         | 23   | 7708   | Olympic_Games |
| Lorenzo     | 11.1        | 7.03      | 13.22    | 1.85      | 49.34       | 15.38       | 40.22  | 4.5        | 58.36    | 263.08         | 24   | 7592   | Olympic_Games |
| Karlivans   | 11.33       | 7.26      | 13.3     | 1.97      | 50.54       | 14.98       | 43.34  | 4.5        | 52.92    | 278.67         | 25   | 7583   | Olympic_Games |
| Korkizoglou | 10.86       | 7.07      | 14.81    | 1.94      | 51.16       | 14.96       | 46.07  | 4.7        | 53.05    | 317            | 26   | 7573   | Olympic_Games |
| Uldal       | 11.23       | 6.99      | 13.53    | 1.85      | 50.95       | 15.09       | 43.01  | 4.5        | 60       | 281.7          | 27   | 7495   | Olympic_Games |
| Casarsa     | 11.36       | 6.68      | 14.92    | 1.94      | 53.2        | 15.39       | 48.66  | 4.4        | 58.62    | 296.12         | 28   | 7404   | Olympic_Games |