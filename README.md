### Jaro

|            | size=3 | size=6 | size=9 | size=12 | size=15 |
| :--------- | -----: | -----: | -----: | ------: | ------: |
| **eddie**  |  0.05  |  0.11  |  0.14  |  0.15   |  0.18   |
| **strsim** |  0.11  |  0.19  |  0.24  |  0.31   |  0.41   |


### Jaro-Winkler

|             | size=3 | size=6 | size=9 | size=12 | size=15 |
| :---------- | -----: | -----: | -----: | ------: | ------: |
| **eddie**   |  0.06  |  0.10  |  0.14  |  0.16   |  0.19   |
| **strsim**  |  0.12  |  0.18  |  0.22  |  0.30   |  0.39   |
| **natural** |  0.32  |  0.87  |  0.99  |  1.56   |  1.64   |


### Levenshtein

|                   | size=3 | size=6 | size=9 | size=12 | size=15 | Notes                       |
| :---------------- | -----: | -----: | -----: | ------: | ------: | :-------------------------- |
| **eddie**         |  0.05  |  0.12  |  0.18  |  0.35   |  0.57   |                             |
| **edit_distance** |  0.15  |  0.19  |  0.26  |  0.49   |  0.60   |                             |
| **strsim**        |  0.13  |  0.23  |  0.27  |  0.43   |  0.64   |                             |
| **txtdist**       |  0.16  |  0.33  |  0.38  |  0.64   |  0.94   | _Does not support Unicode._
| **natural**       |  0.89  |  1.43  |  1.93  |  2.48   |  3.09   | _Does not support Unicode._ |
| **distance**      |  0.89  |  1.45  |  2.12  |  2.96   |  4.10   |                             |


### Damerau-Levenshtein

|              | size=3 | size=6 | size=9 | size=12 | size=15 | Notes                       |
| :----------- | -----: | -----: | -----: | ------: | ------: | :-------------------------- |
| **txtdist**  |  0.50  |  0.94  |  1.93  |  2.60   |  3.97   | _Does not support Unicode._
| **eddie**    |  0.39  |  0.95  |  1.69  |  2.50   |  4.07   |                             |
| **strsim**   |  1.03  |  2.07  |  3.73  |  5.16   |  7.05   |                             |
| **distance** |  1.74  |  3.40  |  5.17  |  7.16   | 10.66   |                             |