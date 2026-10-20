# Forage · KPMG Data Analytics

My work from the [KPMG AU Data Analytics job simulation](https://www.theforage.com/simulations/kpmg-au/data-analytics-y7gh) on Forage, completed in October and November 2022.

The client in the simulation is Sprocket Central, a bike and cycling accessories retailer that shared its customer and transaction data and a list of 1,000 new customers. The first module asked for a data quality review written up for the client, the second for a plan to decide which new customers to target, and the third for a dashboard of the results.

## What is in this repo

| Path | What it is |
| --- | --- |
| `1-data-quality/exploration.ipynb` | My pandas checks of the four worksheets, covering shapes, types, missing values, value counts and ranges. |
| `1-data-quality/data-quality-findings.md` | The nine issues I reported to the client. |
| `2-data-insights/approach.md` | The content of my short deck on how to approach the targeting question. |
| `requirements.txt` | The Python packages the notebook imports. |

## What I found

The review turned up nine issues across three of the worksheets. They include missing values in several customer columns, inconsistent gender entries, unreadable characters in the `default` column, four unnamed columns in the new customer list and a date of birth in 1843.

For the second module I proposed a recommendation system built on the client data plus external data such as ABS population figures. I suggested judging it with two ranking metrics, MAP@K and MAR@K.

## Looking back

The brief asked which of the 1,000 new customers to target, and those customers had no purchase history. A ranked list of customers by likely value would have answered that more directly than the recommender I proposed. I did not keep my work for the third module, the dashboard, so it is not here.

## Running the notebook

1. Install the packages with `pip install -r requirements.txt`.
2. Open `1-data-quality/exploration.ipynb` in Jupyter and run the cells in order.

The notebook reads the workbook from the link the programme used in 2022. The data belongs to the programme, so it is not included here. If that link stops working, enrol in the simulation on Forage, download the workbook and point `dataset_url` at your copy.

Outputs that printed rows of customer or transaction data have been cleared from the saved notebook. The counts and summaries are kept.

## What is not in this repo

I left out everything that was not my own work. That covers the Forage task briefs, the Sprocket Central workbook, the example dashboard and sample report that came with the programme, the client logo and the programme's PowerPoint template. I also left out a scratch notebook from the second module that only loaded the data.

## Licence

My code and writing in this repo are under the [MIT licence](LICENSE). The licence does not cover the Sprocket Central data, the Forage briefs or any KPMG material, and none of those are included here.
