this data was extracted from 
link -> https://cmustatistics.github.io/data-repository/medicine/meningitis.html


Meningitis refers to Inflammation of meninges, which are protective layers that covers the brain. 


this data was collected at Duke University medical center, where they collected using records for all Patients with acute meningitis between jan 1969 and 1980. The researchers used laboratory records to determine which patients had bacterial or viral meniningitis. 


# Data Dictionary

| Variable | Description |
|---|---|
| `year` | Year of the case, written using two digits, such as `78` for 1978. |
| `month` | Month number. |
| `age` | Age of the patient in years. |
| `race` | Race of the patient: Black or White. |
| `sex` | Sex of the patient: male or female. |
| `dx` | Unknown. |
| `priordx` | Unknown. |
| `priorrx` | Whether the patient received antibiotics before admission to the hospital: `0 = no`, `1 = yes`. |
| `wbc` | White blood cell count per 1,000 in a blood sample. |
| `pmn` | Percentage of polymorphonuclear leukocytes in blood. |
| `bands` | Percentage of blood polymorphonuclear leukocytes that are immature band forms. |
| `compns` | Unknown. |
| `daysrx` | Unknown. |
| `offrx` | Unknown. |
| `lptodc` | Unknown. |
| `lpgap` | Hours between the first lumbar puncture and the second, if a second lumbar puncture was conducted. |
| `morelabs` | Unknown. |
| `bloodgl` | Blood glucose level in mg/dL. |
| `gl` | Cerebrospinal fluid glucose level in mg/dL. |
| `pr` | Cerebrospinal fluid protein level in mg/dL. |
| `reds` | Cerebrospinal fluid red blood cell count, count per mm³. |
| `whites` | Total leukocyte count in cerebrospinal fluid, count per mm³. |
| `polys` | Percentage of polymorphonuclear leukocytes in cerebrospinal fluid. |
| `lymphs` | Cerebrospinal fluid lymphocyte count; units not given. |
| `monos` | Unknown; possibly cerebrospinal fluid monocyte percentage. |
| `others` | Unknown; possibly percentage of other white blood cell types in cerebrospinal fluid. |
| `gram` | Gram smear result: `0 = Gram-negative`; positive values mean Gram-positive. |
| `culture` | Unknown. |
| `cie` | Unknown; possibly counterimmunoelectrophoresis test result for specific bacterial antigens, but coding is unclear. |
| `bloodclt` | Unknown. |
| `bloodgl2` | Unknown; possibly blood glucose level at the time of the second lumbar puncture. |
| `gl2` | Cerebrospinal fluid glucose level in the second lumbar puncture. |
| `pr2` | Cerebrospinal fluid protein level in the second lumbar puncture. |
| `reds2` | Cerebrospinal fluid red blood cell count in the second lumbar puncture. |
| `whites2` | Cerebrospinal fluid white blood cell count in the second lumbar puncture. |
| `polys2` | Percentage of polymorphonuclear leukocytes in the second lumbar puncture. |
| `lymphs2` | Cerebrospinal fluid lymphocyte count in the second lumbar puncture. |
| `monos2` | Unknown; possibly cerebrospinal fluid monocyte percentage in the second lumbar puncture. |
| `others2` | Unknown; possibly percentage of other white blood cell types in the second lumbar puncture. |
| `sumbands` | Unknown. |
| `subset` | Assignment to training or test set as defined by the original researchers. |
| `abm` | Final meningitis diagnosis: `1 = acute bacterial meningitis`, `0 = viral meningitis`, determined by cultures and antigen tests. |
