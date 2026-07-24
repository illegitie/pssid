# pSSID Wifi Monitoring Project Report

## 1. Introduction

    This document describes the work completed so far on the pSSID network monitoring project. The goal of the project is to deploy a distributed network measurement system capable of collecting, storing, and visualizing network performance metrics.

    The system uses Raspberry Pi devices as measurement nodes and integrates:
        - pSSID daemon for Wi-Fi monitoring
        - pScheduler for active network measurements
        - OpenSearch for data storage and indexing
        - Grafana for visualisation and dashboards
        - Ansible for automated deployment
        - GUI for creating configurations for pSSID daemons
    
---

## 2. Project Architecture
    