# Mapping Roads for Surface Reflective Cracking Analysis

## Overview
This document outlines the comprehensive workflow for mapping Brooks Road to track surface reflective cracking across different material sections. The process combines drone photogrammetry, LiDAR data, and precision GPS measurements for accurate surface analysis.

## Equipment Required
- DJI Mavic 3E drone
- Topcon Hiper V base and rover
- [Ground Control Points (GCPs)](https://www.amazon.com/Sky-High-Bulls-Eye-Photography-Passthrough/dp/B07JKGZ6DX)
- LiDAR equipped vehicle
- RTK base station
- Data collection tablet/laptop

## Detailed Workflow

### 1. Planning & Site Preparation
- Conduct initial site survey
- Check weather forecast (optimal conditions: clear sky, low wind)
- Identify road segments with different materials
- Mark areas of specific interest
- Prepare equipment checklist

### 2. GCP Setup and Survey
- **GCP Placement Guidelines:**
  - Place pairs 50-100m apart
  - Ensure uniform distribution
  - Avoid placing near road edges
  - Use contrasting targets for better visibility
  
```
Road Edge
|------------------------------------------|
|   GCP1a        GCP2a        GCP3a        |
|   ⚫          ⚫          ⚫         |
|                                          |
|                                          |
|   ⚫          ⚫          ⚫         |
|   GCP1b        GCP2b        GCP3b        |
|------------------------------------------|
Road Edge
```

- **Survey Process:**
  1. Set up Topcon Hiper V base station
  2. Survey each GCP using rover
  3. Record coordinates in RTK mode
  4. Document GCP IDs and locations

### 3. Drone Mission Planning
- **Mavic 3E Settings:**
  ```
  Camera Settings:
  - Resolution: 20MP
  - Format: RAW + JPG
  - ISO: 100-400
  - Shutter Speed: 1/1000 or faster
  - White Balance: Auto
  
  Flight Parameters:
  - Altitude: 50m AGL
  - Speed: 5-8 m/s
  - Image Interval: 5 seconds
  - Overlap: 75% forward, 60% side
  ```

- **Mission Planning Steps:**
  1. Create waypoint mission in DJI Pilot
  2. Set flight parameters
  3. Verify GCP visibility in planned images
  4. Check for obstacles and restricted areas

### 4. Data Collection
- **Drone Operation:**
  1. Verify RTK fix
  2. Execute planned mission
  3. Monitor image capture
  4. Record environmental conditions

- **Supplementary Data:**
  - Collect LiDAR scans
  - Record surface temperature
  - Document material transitions
  - Note any visible defects

### 5. Data Processing
- **Image Processing:**
  1. Import images to RealityCapture
  2. Align images
  3. Import GCP coordinates
  4. Generate dense point cloud
  5. Create orthomosaic

- **Quality Control:**
  ```
  Verification Checklist:
  □ Image alignment quality
  □ GCP accuracy (<2cm error)
  □ Complete coverage
  □ Surface detail visibility
  □ Material boundary clarity
  ```

### 6. Surface Analysis
- Generate crack maps
- Identify material boundaries
- Document surface anomalies
- Create detailed reports

## Data Management
- Organize by date and road section
- Back up raw data
- Document processing parameters
- Maintain coordinate system consistency

## Safety Considerations
- Check airspace restrictions
- Maintain visual line of sight
- Use safety vests and cones
- Monitor traffic conditions

## Quality Assurance
- Verify GCP visibility
- Check image quality
- Validate alignments
- Review final outputs

## Additional Resources
- [DJI Mavic 3E Manual](https://www.dji.com/mavic-3-enterprise)
- [RealityCapture Documentation](https://www.capturingreality.com/realitycapture)
- [Guide to Photogrammetry](https://www.youtube.com/watch?v=jxOCAr_33zA)

## Notes
- Always check local regulations
- Schedule missions during optimal lighting
- Maintain consistent documentation
- Regular equipment calibration
