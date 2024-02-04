import re
import base64
import os
import nltk
import pandas as pd
from google.oauth2.credentials import Credentials
from google.auth.transport.requests import Request
from google_auth_oauthlib.flow import InstalledAppFlow
from googleapiclient.discovery import build
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.metrics import classification_report
# from imblearn.over_sampling import SMOTE
import joblib
from sklearn.pipeline import Pipeline
from imblearn.over_sampling import SMOTE
class SpamClassifier
def create_spam_dataset()
def fetch_emails(service)
