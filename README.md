# k8s-config

## github secrets

all values which are used for a kubernetes secret must be base64 encoded in the github secrets

- API_KEY: base64 encoded
- KUBECONFIG: base64 encoded (kubectl action)
- TELEGRAM_TOKEN: base64 encoded
- KUBECONFIG_RAW (helm action)
- TELEGRAM_ALERT_CHATLIST: chat ids separated by `,` (no whitespaces)
