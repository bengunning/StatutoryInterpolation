# StatutoryInterpolation
The backend for StatutoryInterpolation, an HLS JOLT project which provides revision history for titles of the United States Code.

Run REST API server with server.py.

Server setup:
1. install pip
2. pip install flask
3. pip install enum
4. export FLASK_APP=server.py (set on windows)
5. flask run

Running tests:
1. Navigate to parent directory of test.
2. python -m parent_directory.test_file.

Please note that when writing tests, all tests must begin with "test_".
