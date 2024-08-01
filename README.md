# Bakery
# Bakery

Welcome to the Bakery project! This project showcases a bakery website with a collection of delicious cakes and pastries. The website features a modern, responsive design with a video background and detailed descriptions of baked goods.

## Features

- **Interactive Video Background**: The homepage features a video background of the bakery.
- **Delicious Baked Goods**: Display of various cakes and pastries with detailed descriptions.
- **Responsive Design**: Optimized for different screen sizes and devices.

## Technologies Used

- **HTML**: The structure of the website.
- **CSS**: The styling of the website (included in `styles.css`).
- **Fonts**: Google Fonts for typography.
- **Video**: Background video for the homepage.

## Installation and Setup

To view and run this project locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/Bakery.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd Bakery
    ```

3. **Open `index.html` in a web browser to view the project**.

## CSS Styles

The `styles.css` file contains the following styles for the Bakery project:

- **Body**:
    ```css
    body {
        margin: 0;
        background-color: #fbeee0;
    }
    ```

- **Video Background**:
    ```css
    #myBakery {
        width: 100%;
    }
    ```

- **Header**:
    ```css
    .header {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
    }
    .heading {
        color: #d55b3d;
        font-family: 'Montserrat', sans-serif;
        font-size: 60px;
    }
    ```

- **Images Section**:
    ```css
    .images-section {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
    }
    ```

- **Specials Section**:
    ```css
    .item {
        background-color: #ffbdb0;
        width: 350px;
        height: 580px;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 20px;
    }
    .item-name {
        color: #d55b3d;
        font-family: 'Montserrat', sans-serif;
    }
    ```

- **Media Queries**:
    ```css
    @media all and (max-width: 800px) {
        .wrapper {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        img {
            width: 90%;
        }
        .header {
            flex-direction: column;
            align-items: center;
        }
        .heading-h2,
        .heading {
            font-size: 15px;
        }
        .item {
            width: 100%;
            height: auto;
        }
        #pictures-section {
            margin: 20px 0px;
        }
    }
    ```

## How to Contribute

If you want to contribute to this project, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:

    ```bash
    git checkout -b feature-branch
    ```

3. **Make your changes** and commit them:

    ```bash
    git add .
    git commit -m "Add new feature"
    ```

4. **Push to the branch**:

    ```bash
    git push origin feature-branch
    ```

5. **Create a pull request** on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

