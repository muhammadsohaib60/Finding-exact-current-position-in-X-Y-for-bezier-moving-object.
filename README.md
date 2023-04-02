def get_position(self, fish):
    now = datetime.now()
    now = self.time_now(now)
start = self.time_now(fish.fish_start)
path = self.get_path(fish.fish_type)
elapsed_time = round(now - start)
t = elapsed_time / self.config.move_time[fish.fish_type]
x = path[0][0]
y = path[0][1]
if t != 0.0:
   x = self.the_math(path[0][0], path[1][0], path[2][0], t, 667, 0.85)
   y = self.the_math(path[0][1], path[1][1], path[2][1], t, 375, 0.8)
return x, y
