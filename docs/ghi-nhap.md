# ghi nháp.

- Cài đặt suricata update :

    ```sh
    sudo yum install python-pip python-yaml -y
    sudo pip install --pre --upgrade suricata-update
    ```

- Download source :

    ```sh
    suricata-update
    ```

- Xem list các source : 

    ```sh
    suricata-update list-sources
    ```

- enabled source :

    ```sh
    suricata-update enable-source sslbl/ssl-fp-blacklist
    ```

- list enabled source :

    ```sh
    suricata-update list-enabled-sources
    ```

- Disabled source :

    ```sh
    suricata-update disable-source et/pro
    ```

- Remove source :

    ```sh
    suricata-update remove-source et/pro
    ```