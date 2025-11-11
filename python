import numpy as np
import matplotlib.pyplot as plt

# Parameter
N0 = 500      # jumlah bakteri awal
r = 0.3       # laju pertumbuhan (per jam)
t = np.linspace(0, 10, 200)  # waktu (jam)

# Fungsi populasi
N = N0 * np.exp(r * t)

# Plot
plt.figure(figsize=(10, 6))
plt.plot(t, N, color='green', label='Jumlah Bakteri N(t)')
plt.axhline(500, color='gray', linestyle='--', label='Awal (500)')
plt.title('Model Pertumbuhan Bakteri Eksponensial')
plt.xlabel('Waktu (jam)')
plt.ylabel('Jumlah Bakteri')
plt.grid(True)
plt.legend()
plt.show()
