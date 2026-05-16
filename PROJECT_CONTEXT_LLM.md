{
  "project": "LimeSDR USB RF-shielded CNC case",
  "purpose": [
    "mechanical protection",
    "thermal dissipation",
    "RF/control area separation and shielding"
  ],
  "primary_deliverables": [
    "bottom.step",
    "top.step",
    "bottom.f3d",
    "top.f3d",
    "Laser_Marking.dwg"
  ],
  "manufacturing_target": "JLCCNC / JLCPCB CNC",
  "thermal_interface": {
    "recommended_pad_nominal_mm": 1.0,
    "expected_compression_mm": [0.4, 0.7],
    "note": "Use soft thermopad to avoid PCB stress."
  },
  "fan": {
    "mount": "4010 (40x40x10)",
    "cable_hole_mm": 6.0,
    "lime_header_voltage_v": 3.3
  },
  "assembly_hardware": {
    "case_halves": "M4x30",
    "pcb_mount": "M3x4 flat head",
    "fan_mount": "M2.5 or M3 (holes modeled for M2.5)"
  },
  "rf_cables": {
    "rf_side": {
      "recommended_type": "RG113",
      "recommended_length_mm": 75,
      "count": 10
    },
    "clock_side": {
      "type": "RG178",
      "recommended_length_mm": "75-100",
      "count": 2
    }
  },
  "images_folder": "images/",
  "readme": "README.md"
}

