# Kafka
Apache Kafka  

### Setup

1. **Clone and install dependencies**:
```bash
git clone https://github.com/404-dev-notFound/Kafka.git
pip install confluent-kafka
```

2. **Start the Docker**:
```bash
compose -f 'docker-compose.yaml' up -d --build 'kafka'
```

3. **Run the Producer and Tracker**:
```bash
python producer.py
python tracker.py
```
