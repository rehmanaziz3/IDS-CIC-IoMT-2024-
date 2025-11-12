# IDS-CIC-IoMT-2024-
Purpose: To provide a realistic dataset for developing and evaluating Intrusion Detection Systems (IDS) in healthcare IoT environments.
Devices: 40 IoMT devices, including real medical sensors and simulated ones.

Protocols: Covers healthcare-relevant protocols like Wi-Fi, MQTT, Bluetooth, and others.

Attacks: 18 distinct attack scenarios executed against the IoMT testbed.

Attack Classes:

DDoS

DoS

Reconnaissance

MQTT-specific attacks

Spoofing

📊 Why It Matters
Healthcare focus: Unlike general IoT datasets (like CIC-DIAD 2024), CIC-IoMT 2024 is tailored to medical IoT devices, making it highly relevant for securing hospital and patient-care systems.

Multi-protocol coverage: Since healthcare devices often use diverse communication protocols, this dataset helps researchers design IDS solutions that can handle heterogeneous traffic.

Ground truth labels: Each flow is tagged with its attack type, enabling supervised ML and deep learning approaches.

Complementary dataset: It complements CIC’s other datasets (like CIC-DIAD 2024 for IoT anomaly detection) by focusing specifically on medical IoT security.

⚡ How Researchers Use It
Preprocessing: Merge CSVs, normalize labels, and handle imbalanced attack distributions.

Feature Engineering: Extract flow-based features (packet length, flags, timing) and protocol-specific features (MQTT message types).

Model Training:

Classical ML (Random Forest, SVM).

Deep learning (CNN, RNN, Transformers).

Hybrid IDS combining signature-based and anomaly detection.

Evaluation: Accuracy, precision, recall, F1-score, plus robustness against protocol-specific attacks.

==================================================================================Rehman Aziz ================================================================================
