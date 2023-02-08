# timeseries-production-forecast

Values on table below are presented as MAPE score (lower is better)

| Model                | Univariate (month) | Univariate (daily) | PastCovar (month) | PastCovar (daily) |
|----------------------|--------------------|--------------------|-------------------|-------------------|
| ExponentialSmoothing | 3.64               | 2.93               | --                | --                |
| RNN:LSTM             | 3.83               | 4.80               | --                | --                |