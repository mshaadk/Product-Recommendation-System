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
    git clone https://github.com/mshaadk/Product-Recommendation-System.git
    cd Product-Recommendation-System
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Make sure you have the data files `data.pkl` and `similarity.pkl` in the same directory.

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

## 📊 Data

- **data.pkl**: Contains the product data including names and image URLs.
- **similarity.pkl**: Contains the precomputed similarity matrix used for recommending similar products.


## 📌 Background Image

The app uses a custom background image that can be changed in the code. Simply modify the URL in the `set_bg_from_url` function.

## 👤 Author

**Mohamed Shaad**

- LinkedIn: [@Mohamed Shaad](https://www.linkedin.com/in/mohamedshaad)
- GitHub: [@mshaadk](https://github.com/mshaadk)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.
