# ImageMatch Project

## Project Overview

ImageMatch is an advanced image matching and similarity analysis application that combines backend image processing capabilities with a React frontend.

## Demo

[Watch the Demo]([https://drive.google.com/file/d/VIDEO_ID/view](https://www.dropbox.com/scl/fi/rokz1ksdsdypu05bfw5xh/ImageMatch.mp4?rlkey=eolesj51au529nogb2dj32mq4&st=uv0g5yg4&dl=0%2Fview))


## Team

The project is built by the team consisting of:

- Marouan Daghmoumi
- Mohammed Aachabi
- Abdelmajid Benjelloun

The project is supervised and guided by Professor M'hamed AIT KBIR.

## Project Structure

```
ImageMatch-app/
│
├── backend/
│   ├── app.py                 # Main backend application
│   ├── image_utils.py         # Image utility functions
│   ├── relevance_feedback.py  # Relevance feedback mechanism
│   ├── similarity.py          # Image similarity calculations
│   ├── static/                # Static files
│   ├── uploads/               # Uploaded image storage
│   └── processed/             # Processed image descriptors
│
├── rsscn7-front-main/         # React Frontend
│   ├── src/
│   │   ├── components/        # React components
│   │   ├── App.js             # Main React application
│   │   └── ...
│   └── package.json           # Frontend dependencies
│
├── descriptors_calculation/   # (Optional) Descriptor calculation scripts
│
├── venv/                      # Python virtual environment
├── requirements.txt           # Python backend dependencies
└── README.md                  # Project documentation
```

## Prerequisites

- Python 3.8+
- Node.js 14+
- npm (Node Package Manager)

## Setup and Installation

### Backend Setup

1. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd rsscn7-front-main
   ```

2. Install npm packages:
   ```bash
   npm install
   ```

## Running the Application

### Start Backend

```bash
# From the project root
python backend/app.py
```

### Start Frontend

```bash
# Navigate to frontend directory
cd rsscn7-front-main
npm start
```

## Key Components

### Backend (`backend/`)
- `app.py`: Main Flask application
- `image_utils.py`: Image processing utilities
- `similarity.py`: Image similarity calculation methods
- `relevance_feedback.py`: Implement feedback-based similarity refinement

### Frontend (`rsscn7-front-main/`)
- React-based web interface
- Components for different image analysis features
- Authentication and image management

## Features

- Image similarity matching
- Multiple descriptor calculations (Gabor, Hu Moments, Histogram)
- Relevance feedback mechanism
- Dominant color analysis
- Interactive frontend for image management

## Configuration

- `backend/weights_config.json`: Configure descriptor weights
- `backend/weights_history.json`: Track weight adjustments
- `backend/histogram.json`: Store histogram-related configurations

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Specify your project's license here (e.g., MIT, Apache 2.0)
