FROM python

# Create app directory
RUN mkdir -p /backend
WORKDIR /backend

# Copy app source code
COPY . /backend

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt