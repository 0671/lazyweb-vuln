# LazyWeb -


## Deployment Instructions
To get started with the project, simply run the following command:

```bash
docker-compose up
```

This will set up the environment and start the application using Docker.

### Important Notes
- Ensure that the `templates_c` and `user/avatar` directories have the correct ownership. After deploying, run:
  
  ```bash
  sudo chown www-data:www-data templates_c user/avatar
  ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
