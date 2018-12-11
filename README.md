# Estimating-Pi
as = 4
pa = a/as
area of circle = (pi)r^2 if r = 1, then area of circle = pi, area of circle will be pa*as

function z(q,r,a,n)
           for i = 1:n
               if q < 1 && r < 1
                   t = q^2 + r^2
               end
                 if t < 1
                   a += 1
                 end
           q = 1-2rand()
           r = 1-2rand()
           end
       as = 4
       pc = a/n
       ac = pc*4
       println(ac)
       end
