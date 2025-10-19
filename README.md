# BitHealth Triage Recommender Service

### Prerequisites

1.  Python 3.11
2.  'pip'

### Setup

1.  **Klon repositori dan masuk ke direktori**
2.  **Instal semua dependensi yang diperlukan:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Isi file .env dengan gemini API key, serta model LLM yang ingin digunakan**

### Running the Server

Jalankan aplikasi menggunakan **Uvicorn**

```bash
uvicorn app:app --host {your_host} --port {yout_port}
