# Total de solicitudes
total = len(df)

# Solicitudes exitosas y con error
success_df = df[df['success'] == True]
error_df = df[df['success'] == False]

total_success = len(success_df)
total_error = len(error_df)
error_pct = (total_error / total) * 100

# Estadísticas de tiempo solo para exitosas (campo 'elapsed' está en ms)
mean_resp = success_df['elapsed'].mean()
min_resp = success_df['elapsed'].min()
max_resp = success_df['elapsed'].max()
p90 = success_df['elapsed'].quantile(0.9)
p95 = success_df['elapsed'].quantile(0.95)
p99 = success_df['elapsed'].quantile(0.99)

# Threads que tardaron > 1500 ms (1.5 seg) en exitosas y en total
threads_above_1_5s_success = len(success_df[success_df['elapsed'] > 1500])
threads_above_1_5s_total = len(df[df['elapsed'] > 1500])

print(f"Total de threads (solicitudes): {total}")
print(f"Solicitudes exitosas: {total_success}")
print(f"Solicitudes con error: {total_error} ({error_pct:.2f}%)\n")

print("Estadísticas de tiempo (solo exitosas):")
print(f"Tiempo medio de respuesta     : {mean_resp:.2f} ms")
print(f"Tiempo mínimo de respuesta    : {min_resp:.2f} ms")
print(f"Tiempo máximo de respuesta    : {max_resp:.2f} ms")
print(f"Percentil 90                  : {p90:.2f} ms")
print(f"Percentil 95                  : {p95:.2f} ms")
print(f"Percentil 99                  : {p99:.2f} ms\n")

print(f"Threads > 1.5 segundos (exitosas): {threads_above_1_5s_success} ({(threads_above_>
# Total de solicitudes
total = len(df)

# Solicitudes exitosas y con error
success_df = df[df['success'] == True]
error_df = df[df['success'] == False]

total_success = len(success_df)
total_error = len(error_df)
error_pct = (total_error / total) * 100

# Estadísticas de tiempo solo para exitosas (campo 'elapsed' está en ms)
mean_resp = success_df['elapsed'].mean()
min_resp = success_df['elapsed'].min()
max_resp = success_df['elapsed'].max()
p90 = success_df['elapsed'].quantile(0.9)
p95 = success_df['elapsed'].quantile(0.95)
p99 = success_df['elapsed'].quantile(0.99)

# Threads que tardaron > 1500 ms (1.5 seg) en exitosas y en total
threads_above_1_5s_success = len(success_df[success_df['elapsed'] > 1500])
threads_above_1_5s_total = len(df[df['elapsed'] > 1500])

print(f"Total de threads (solicitudes): {total}")
print(f"Solicitudes exitosas: {total_success}")
print(f"Solicitudes con error: {total_error} ({error_pct:.2f}%)\n")

print("Estadísticas de tiempo (solo exitosas):")
print(f"Tiempo medio de respuesta     : {mean_resp:.2f} ms")
print(f"Tiempo mínimo de respuesta    : {min_resp:.2f} ms")
print(f"Tiempo máximo de respuesta    : {max_resp:.2f} ms")
print(f"Percentil 90                  : {p90:.2f} ms")
print(f"Percentil 95                  : {p95:.2f} ms")
print(f"Percentil 99                  : {p99:.2f} ms\n")

print(f"Threads > 1.5 segundos (exitosas): {threads_above_1_5s_success} ({(threads_above_>
# Total de solicitudes
total = len(df)

# Solicitudes exitosas y con error
success_df = df[df['success'] == True]
error_df = df[df['success'] == False]

total_success = len(success_df)
total_error = len(error_df)
error_pct = (total_error / total) * 100

# Estadísticas de tiempo solo para exitosas (campo 'elapsed' está en ms)
mean_resp = success_df['elapsed'].mean()
min_resp = success_df['elapsed'].min()
max_resp = success_df['elapsed'].max()
p90 = success_df['elapsed'].quantile(0.9)
p95 = success_df['elapsed'].quantile(0.95)
p99 = success_df['elapsed'].quantile(0.99)

# Threads que tardaron > 1500 ms (1.5 seg) en exitosas y en total
threads_above_1_5s_success = len(success_df[success_df['elapsed'] > 1500])
threads_above_1_5s_total = len(df[df['elapsed'] > 1500])

print(f"Total de threads (solicitudes): {total}")
print(f"Solicitudes exitosas: {total_success}")
print(f"Solicitudes con error: {total_error} ({error_pct:.2f}%)\n")

print("Estadísticas de tiempo (solo exitosas):")
print(f"Tiempo medio de respuesta     : {mean_resp:.2f} ms")
print(f"Tiempo mínimo de respuesta    : {min_resp:.2f} ms")
print(f"Tiempo máximo de respuesta    : {max_resp:.2f} ms")
print(f"Percentil 90                  : {p90:.2f} ms")
print(f"Percentil 95                  : {p95:.2f} ms")
print(f"Percentil 99                  : {p99:.2f} ms\n")

print(f"Threads > 1.5 segundos (exitosas): {threads_above_1_5s_success} ({(threads_above_1_5s_success/total_success)*100:.2f}%)")
print(f"Threads > 1.5 segundos (total)   : {threads_above_1_5s_total} ({(threads_above_1_1_5s_total/total)*100:.2f}%)")
