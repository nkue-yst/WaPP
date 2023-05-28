# コンパイラとフラグ
CXX := g++
CXXFLAGS := -std=c++11 -Wall -I../include

# ソースファイルの検出と実行ファイル名の生成
SOURCES := $(wildcard *.cpp)
EXECUTABLES := $(SOURCES:.cpp=)

# ビルドターゲット
all: $(EXECUTABLES)

# オブジェクトファイルの生成ルール
%.o: %.cpp
	$(CXX) $(CXXFLAGS) -c $< -o $@

# 実行ファイルの生成ルール
%: %.o
	$(CXX) $(CXXFLAGS) $< -o $@

# クリーンアップターゲット
clean:
	rm -f $(EXECUTABLES) $(SOURCES:.cpp=.o)
