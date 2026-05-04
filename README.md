# Cecilia-882-IntelligenceCecilia-882-Intelligence
An AI-driven network traffic classifier created by Blackbox Group for real-time fraud detection."
"""
Cecilia 882 Intelligence Engine
Production-grade network threat detection system
"""

__version__ = "2.0.0"
__author__ = "Security Team"
__license__ = "MIT"

from .engine import (
    Cecilia882Intelligence,
    NetworkFlow,
    AnalysisResult,
    AlertSeverity,
    FlowAction,
    InputValidator,
    MLModelLoader,
    SecureAuditLogger,
    ThreadSafeMetrics
)

__all__ = [
    "Cecilia882Intelligence",
    "NetworkFlow",
    "AnalysisResult",
    "AlertSeverity",
    "FlowAction",
    "InputValidator",
    "MLModelLoader",
    "SecureAuditLogger",
    "ThreadSafeMetrics"
]
