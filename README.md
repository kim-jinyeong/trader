# trader

필요 library

python 3.6

pytorch 1.8.0

numpy

pandas

tqdm

matplotlib

mplfinance


cmd main.py 파일 위치에서 실행 

(lstm)
python main.py --mode train --ver v3 --name 035720 --stock_code 035720 --rl_method a2c --net lstm

(cnn)
python main.py --mode train --ver v3 --name 035720 --stock_code 035720 --rl_method a2c --net cnn
