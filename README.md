# EA - Your Personal AI Friend and Healer

![EA Logo](images/ea-logo.png)

## Overview
**EA** is a private personal AI designed to provide companionship and assistance to individuals dealing with health issues, depression, and memory challenges. EA offers familiar conversation and reliable support, aiming to improve overall well-being and quality of life.

## Features
- **Health Monitoring**: Track your physical health metrics and receive personalized advice.
- **Mental Health Support**: Engage in comforting conversations and receive strategies to manage depression and anxiety.
- **Memory Assistance**: Get reminders and help with organizing daily tasks to manage memory issues.
- **Companionship**: Enjoy meaningful and familiar conversations to combat loneliness.

## Getting Started
To get started with EA, follow these steps:

### Prerequisites
- PHP 8.0+
- Composer
- Web server (Apache, Nginx, etc.)

### Installation
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/ea-ai-friend.git
    cd ea-ai-friend
    ```

2. **Install Dependencies**:
    ```sh
    composer install
    ```

3. **Set Up Environment Variables**:
    Create a `.env` file in the root directory and add the following:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

4. **Configure Web Server**:
    Ensure your web server is set up to serve the application. For Apache, you might add a virtual host configuration like:
    ```apache
    <VirtualHost *:80>
        ServerName ea.local
        DocumentRoot /path/to/ea-ai-friend/public
        <Directory /path/to/ea-ai-friend/public>
            AllowOverride All
            Require all granted
        </Directory>
    </VirtualHost>
    ```

5. **Run the Application**:
    Ensure your web server is running and navigate to your application's URL in your browser.

## Usage
Once the application is running, EA will be available to interact with you through the web interface. Simply type your queries or responses, and EA will engage in a conversation to provide the assistance you need.

### Example Commands
- **Health Check**:
    ```sh
    EA, how is my health today?
    ```
- **Mental Health Support**:
    ```sh
    EA, I'm feeling down. Can you help?
    ```
- **Memory Assistance**:
    ```sh
    EA, remind me to take my medication at 8 PM.
    ```

## Contributing
We welcome contributions to improve EA. To contribute, please follow these steps:

1. **Fork the Repository**:
    Click on the "Fork" button at the top right of this repository page.

2. **Create a Feature Branch**:
    ```sh
    git checkout -b feature/your-feature-name
    ```

3. **Commit Your Changes**:
    ```sh
    git commit -m 'Add some feature'
    ```

4. **Push to the Branch**:
    ```sh
    git push origin feature/your-feature-name
    ```

5. **Open a Pull Request**:
    Submit your pull request, describing the changes you made.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions, suggestions, or feedback, please reach out to us at [email@example.com](mailto:email@example.com).

---

Thank you for choosing EA as your personal AI friend and healer. We hope EA brings you comfort, support, and improved well-being.
