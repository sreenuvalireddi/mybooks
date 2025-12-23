https://upgraded-fiesta-r474jwrj65x4cr49-5173.app.github.dev/


npm run dev


https://upgraded-fiesta-r474jwrj65x4cr49.github.dev/


docker build -t myapp-shopper-ui .

docker run -p 8080:80 myapp-shopper-ui


docker push valireddisreenu/myapp-shopper-ui:release-1.0

docker tag myapp-shopper-ui valireddisreenu/myapp-shopper-ui:release-1.0 && docker images | grep myapp-shopper-ui
