---
type: ProjectLayout
title: The Sky Cluster
date: '2024-10-08'
client: 2024 NASA Space Apps Challenge
description: >-
  A flutter crossplataform that allows users to experience a starry night from
  an exoplanet of their choice, learn about the planet and create unique
  constellations. Its importance relies on the complexity of most databases that
  makes the information inaccesible for most people.
featuredImage:
  type: ImageBlock
  url: /images/dark.png
  altText: Project thumbnail image
media:
  type: ImageBlock
  url: /images/mobidark.png
  altText: Project image
bottomSections: []
metaTags: []
colors: colors-a
---
A simple yet interactive Mars Weather App that provides real-time data from NASA's InSight mission. This project fetches the latest weather information from Mars and displays it in a responsive, modern UI. The app also includes light and dark theme modes to enhance the user experience. Currently hosted on AWS. <https://d1f83oux5dkefi.cloudfront.net/>

InSight: Mars Weather Service API
NASA’s InSight Mars lander takes continuous weather measurements (temperature, wind, pressure) on the surface of Mars at Elysium Planitia, a flat, smooth
plain near Mars’ equator. Please note that there are sometimes problems with the sensors on Mars that result in missing data! If you see a long gap, a search
result may bring up more information on whether it is a long-lasting problem. Summaries of these data are available at <https://mars.nasa.gov/insight/weather/>.
This API provides per-Sol summary data for each of the last seven available Sols (Martian Days). As more data from a particular Sol are downlinked from the
spacecraft (sometimes several days later), these values are recalculated, and consequently may change as more data are received on Earth. Additionally,
please note that wind and other sensor data may not exist for certain date ranges. You can check out <https://mars.nasa.gov/insight/weather/> and scroll down to
the 'seasonal weather report' you'll see the gaps where no data exists for some sensors
