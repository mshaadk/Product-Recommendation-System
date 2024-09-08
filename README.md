# 📦 Product Recommendation System

This is a simple Product Recommendation System built with Streamlit that recommends similar products based on a selected item. The system uses precomputed similarity scores and provides a user-friendly interface for browsing product recommendations.

## 🔍 Features

- **Product Selection:** Users can select a product from the list, and the system will return the top 3 similar products.
- **Image Display:** Recommendations are displayed with images and product names.
- **Custom Background:** Includes a custom background for a visually appealing UI.
- **Responsive Design:** The layout adapts to different screen sizes and displays the recommended products in columns.
- **Footer:** A stylish footer with links to LinkedIn and GitHub profiles.

## 🛠️ Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/shaadclt/product-recommendation-system.git
    cd product-recommendation-system
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Make sure you have the data files `data.pkl` and `similarity.pkl` in the `data/` directory.

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

## 📊 Data

- **data.pkl**: Contains the product data including names and image URLs.
- **similarity.pkl**: Contains the precomputed similarity matrix used for recommending similar products.

## 🖼️ Example

After selecting a product, the app will display something like this:

![App Example](https://img.freepik.com/free-vector/wearable-technology-isometric-flowchart_1284-19018.jpg?w=740&t=st=1723049490~exp=1723050090~hmac=2c52cc76824ba2a41475065bfe62e7f2444cbf92e98fa242dee67ab7242e2b26)

## 📌 Background Image

The app uses a custom background image that can be changed in the code. Simply modify the URL in the `set_bg_from_url` function.

## 👤 Author

**Mohamed Shaad Kunhimohamed**

- LinkedIn: [@Mohamed Shaad](https://www.linkedin.com/in/mohamedshaad)
- GitHub: [@shaadclt](https://github.com/mshaadk)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.
