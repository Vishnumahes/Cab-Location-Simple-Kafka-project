
# Photogram

Photogram is a dynamic photo-sharing web application developed using PHP, HTML, CSS, JavaScript, and MySQL/MongoDB for efficient data management. This project demonstrates the implementation of user registration, photo uploads, and like/unlike functionality with a responsive interface and enhanced security features.

## Features

- **User Registration**: Users can create accounts and manage their profiles.
- **Photo Uploads**: Users can upload photos to share with others.
- **Like/Unlike Functionality**: Users can like or unlike photos.
- **Responsive Design**: Optimized for various devices using HTML5 and CSS3.
- **RESTful APIs**: Implemented for seamless client-server communication.
- **Database Management**: Efficient data handling using MySQL and MongoDB.
- **Security**: Enhanced security following OWASP guidelines.
- **Continuous Integration**: CI/CD pipelines with Git, GitHub, and Docker for automated deployment.

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript, jQuery
- **Backend**: PHP, Node.js
- **Databases**: MySQL, MongoDB
- **Tools**: Git, GitHub, Docker
- **Frameworks**: Bootstrap, Docker Compose

## Installation

### Prerequisites

- PHP 7.0 or higher
- MySQL or MongoDB
- Docker (for containerization)

### Steps

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/Vishnumahes/photogram.git
   cd photogram
   \`\`\`

2. Install dependencies and set up the database:
   - MySQL:
     \`\`\`bash
     mysql -u root -p
     CREATE DATABASE photogram;
     USE photogram;
     SOURCE __migrations.sql;
     \`\`\`

   - MongoDB:
     \`\`\`bash
     mongorestore --db photogram path/to/mongodb/dump
     \`\`\`

3. Configure environment variables (e.g., database credentials) in a `.env` file.

4. Start the application:
   \`\`\`bash
   php -S localhost:8000
   \`\`\`

5. Access the application in your browser:
   \`\`\`
   http://localhost:8000
   \`\`\`

### Docker

Alternatively, you can use Docker for containerization:
\`\`\`bash
docker-compose up
\`\`\`

## Usage

1. Register for a new account or log in with existing credentials.
2. Upload photos and share them with the community.
3. Like or unlike photos posted by others.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   \`\`\`bash
   git checkout -b feature-branch
   \`\`\`
3. Make your changes and commit them:
   \`\`\`bash
   git commit -m "Add some feature"
   \`\`\`
4. Push to the branch:
   \`\`\`bash
   git push origin feature-branch
   \`\`\`
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by popular photo-sharing platforms.
- Thanks to all contributors and developers who helped make this project possible.
