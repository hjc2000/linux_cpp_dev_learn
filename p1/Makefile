# 最后输出的可执行文件的依赖项

# 主规则
object=main.o Print.o 
main: $(object)
	g++ -o main $(object)

# 编译规则
%.o: %.c
	g++ -c $<

# 清理工程
.PHONY : clean
clean:
	rm -f *.o
	rm -f main