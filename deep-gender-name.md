{\rtf1\ansi\ansicpg1252\cocoartf1671\cocoasubrtf100
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;\red25\green25\blue25;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c12941\c12941\c12941;\cssrgb\c100000\c100000\c100000;}
\margl1440\margr1440\vieww28600\viewh18000\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs128 \cf2 \cb3 \expnd0\expndtw0\kerning0
Deep-Gender-Name
\fs28 \

\fs32 This recurrent neural network classifies a given first name as either male or female. This model will use a 2-layer LSTM model with a dense-activation layer and dropout regularization. This decision was through multiple trials with 1-3 layer LSTM models using various dropout rates and batch sizing. The configuration of batch_size = 32 was found to be the most efficient while being as accurate as possible. The model converges in less than 6 epochs and is able to achieve 89% accuracy. }