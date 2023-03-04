# 最后输出的可执行文件的依赖项

# 主规则
main: $(object)
	g++ -o main $(object)

# .o 文件规则
main.o: main.cpp
	g++ -c main.cpp
object=main.o
Print.o: Print.cpp
	g++ -c Print.cpp
object+=Print.o

# 清理工程
clean:
	rm -f *.o
	rm -f main