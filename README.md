# Apache APISIX Configuration Repository  

Welcome to the **Apache APISIX Configuration Repository**! 🎉  

This repository is designed as a learning resource for those who want to explore and understand the capabilities of **Apache APISIX**, a cloud-native and highly customizable API Gateway maintained by the **Apache Software Foundation**.  

If you're new to Apache APISIX or API Gateways in general, this setup provides a hands-on way to learn and experiment. For a deep dive into the features and architecture of APISIX, check out this article:  
👉 [Apache APISIX: Um API Gateway Robusto e Personalizável que Você Deve Aprender](https://tiagotartari.net/apache-apisix-um-api-gateway-robusto-e-personalizavel-que-voce-deve-aprender.html)  

---

## 📖 About This Repository  

This repository contains essential files to set up a Docker-based environment for Apache APISIX, including:  

- **`docker-compose.yml`**:  
  Configures a basic environment with the APISIX core, etcd, and the APISIX Dashboard.  

- **`apisix/conf/config.yaml`**:  
  Core configuration for the APISIX gateway, defining routes, admin keys, and plugin settings.  

- **`apisix_dashboard/conf/conf.yaml`**:  
  Configuration for the APISIX Dashboard, managing user authentication and integration with etcd.  