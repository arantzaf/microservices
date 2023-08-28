FROM python:3.7.3-stretch

## Complete Step 1:
WORKDIR /app

## Complete Step 2:
COPY . app.py /app/

## Complete Step 3:
# Install packages from requirements.txt
# hadolint ignore=DL3013
RUN pip install --no-cache-dir --upgrade pip && pip install --no-cache-dir -r requirements.txt
    
## Complete Step 4:
EXPOSE 80

## Complete Step 5:
# Run app.py at container launch
CMD ["python", "app.py"]
