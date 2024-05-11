# balancer-lab

Docker-based project designed to facilitate understanding and experimentation with different load balancing strategies using NGINX and HAProxy.
This project sets up a simple environment where both NGINX and HAProxy serve as load balancers to distribute incoming requests to multiple backend servers.

## Features

- **NGINX Load Balancing**: Utilizes NGINX as a load balancer to route traffic efficiently between multiple backend services.
- **HAProxy Load Balancing**: Employs HAProxy for robust handling of high traffic loads across multiple servers.
- **Easy Setup**: All components run in Docker containers, ensuring a consistent and isolated environment for testing and development.

## Getting Started

To get started with balancer-lab, clone this repository and ensure you have Docker and Docker Compose installed on your machine.

1. Clone the repository:
```
git clone https://github.com/ck0ba/balancer-lab.git
cd balancer-lab
```

2. Build and run the containers:
```
docker-compose up
```

3. Access the load balancers:
- NGINX at `localhost:8080`
- HAProxy at `localhost:8081`

## Usage
This project is intended for educational purposes to demonstrate the basics of load balancing in a controlled, local environment.
You can modify the configuration files for NGINX and HAProxy to experiment with different load balancing algorithms and settings.

## Contributing
Contributions to BalancerLab are welcome! Whether it's bug fixes, enhancements, or new features, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
