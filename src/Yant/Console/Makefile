
target = yant.exe

nlog_ref = ../../../packages/NLog.4.3.4/lib/net45/NLog.dll

all: $(target)

$(target): EntryPoint.n Framework.n
	ncc -r $(nlog_ref) $^ -o $@
