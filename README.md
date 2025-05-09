# Phone Sales Data Cleaning and Visualization
## This project focuses on cleaning and preparing a smartphone sales dataset using Python (Pandas) for visualization in Tableau. The dataset includes information on brands, models, memory, storage, color, prices, discounts, and ratings.

## Project Structure

- `code/` – Python code for cleaning and initial exploration
- `data/` – raw and cleaned datasets
- `dashboard` - Tableau dashboard packaged file
- `.gitignore` – Files to exclude from version control (e.g., large CSVs)
- `LICENSE` – Open-source license (MIT)
- `README.md` – Project overview and instructions

### Data Source

The dataset used in this project was obtained from Kaggle:

- [Smartphones Sales Dataset on Kaggle]([https://www.kaggle.com/datasets/your-dataset-link](https://www.kaggle.com/datasets/yaminh/smartphone-sale-dataset/data))

The data includes details on smartphone sales in India.

## Data Cleaning (Python)

- Removed or standardized inconsistent values (e.g., "Expandable Upto 32 GB" → 32)
- Converted storage and memory columns to numeric GB values
- Extracted simplified color labels (e.g., "Jet Black" → "black")
- Calculated `selling_price_usd` based on current exchange rate
- Dropped unnecessary columns like `Camera` and handled missing values appropriately

## Visualization (Tableau)

Built an interactive dashboard to explore:
- Brand-wise revenue
- Price distributions by storage
- Discount percentages by brand
- Discount and rating trends
- Sales price and rating trends
- Currency toggle (INR/USD) for dynamic revenue views
- Popular color preferences

### View the Dashboard
You can view the interactive Tableau dashboard here:  
- [Phone Sales Dashboard on Tableau Public](https://public.tableau.com/views/PhoneSales_17467392914450/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

