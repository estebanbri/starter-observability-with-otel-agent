Caracteristica propias de este proyecto:
- ***Tipo de instrumentación → Automatica***. (Es decir se embebió el agente de OpenTelemetry (.jar) directamente en la aplicación) https://opentelemetry.io/docs/instrumentation/java/automatic/
- ***Tipo deployment del collector → No Collector*** (Es decir no implementa un collector externo, el agente otel que se encuentra embebido en la aplicacion se conecta directamente a los destinos de observability) https://opentelemetry.io/docs/collector/deployment/no-collector/
