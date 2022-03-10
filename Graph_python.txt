
import matplotlib.pyplot as  FUNCTION_GRAPH

 
def FUNCTION_INFO_GRAPH():

  #Setting Value
  x_a = 23 # number user 2564y
  x_b = 7  # number user 2565y
  z_a = 22 # pay with payment
  z_b = 8  # pay with money
  ranges = 2 # number bar 
  MAIN_TITLE = "Display Graph"; # Title main
  TITLE_A = "HEADER A" # Title Graph A
  TITLE_B = "HEADER B" # Title Graph B
  NAME_X = ("2564","2565"); # year
  NAME_Z = ("PAYMENT","MONEY"); # pay
  xl = "using2564 =23 , using2565 =7" # Txt.info A
  xx = "usingpay =22  , usingmoney =8"# Txt.info B
  

  X = range(ranges) # define value bar 
  Y = (x_a,x_b)     # define value 2564,2565
  W =range(ranges)  # define value bar
  Z =(z_a,z_b)      # define value payment , money
  FIG = FUNCTION_GRAPH.figure(MAIN_TITLE); #define name title main
  
 
  FIG.add_subplot(121) # create graph A
  FUNCTION_GRAPH.title(TITLE_A) # create header graph
  FUNCTION_GRAPH.bar(X,Y) #create bar graph
  FUNCTION_GRAPH.xticks(X,NAME_X) #chang name[] int number > string 
  FUNCTION_GRAPH.xlabel(xl) #detail info using

  
  FIG.add_subplot(122) # create graph B
  FUNCTION_GRAPH.title(TITLE_B) # create header graph
  FUNCTION_GRAPH.bar(W,Z ,color = "green") #create bar graph chang color
  FUNCTION_GRAPH.xticks(X,NAME_Z) #chang name[] int number > string 
  FUNCTION_GRAPH.xlabel(xx) #detail info using
  FUNCTION_GRAPH.show() # getchar () Display Terminal
  
if __name__ == '__main__':  # == void Mian
  FUNCTION_INFO_GRAPH() # function

  # ติดตั้ง Library matplotlib 
  # คำสั่ง [ pip install matplotlib ] cmd , shell , terminal <
  # ให้รวม MODULE 
  # คำสั่ง import INFO_GRAPH_DISPLAY
  # เรียกใช้ Function FUNCTION_INFO_GRAPH() ใน if __name__ == '__main__':
