# Pricing Module V2

Welcome to **Pricing Module V2**!

## Getting Started
1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/pricing_module_v2.git
    cd pricing_module_v2
    ```

2. (Optional but Recommended) Create and activate a virtual environment:

    ```bash
    # Windows
    python -m venv venv
    venv\Scripts\activate

    # macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install project dependencies:
    ```bash
    pip install -r requirements.txt
    ```


4. Database Setup:
    ```bash
    python manage.py migrate
    ```

5. Create a superuser for admin access:
    ```bash
    python manage.py createsuperuser
    ```

6. Run the server:
    ```bash
    python manage.py runserver
    ```

