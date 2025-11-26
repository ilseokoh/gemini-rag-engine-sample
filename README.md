# Vertex AI RAG Engine with Gemini 2.5 Flash

## RAG Engine 

1. CSV형식을 되어 있는 데이터를 JSONL로 변환, JSONL파일 GCS로 업로드(csv2jsonl.ipynb)
1. GCP Console 에서 RAG Corpus 생성
1. RAG Engine에서 검색 및 Grounding with Gemini (parsed_jsonl_rag_engine_test.ipynb)

## TTL File (Tuttle file format) with Gemini 

Tuttle 파일을 Gemini 에게 설명을 요청. (gemini-ttl-file.ipynb)


## Gemini 호출 기본 코드 (file 첨부)

gemini-call-with-file.ipynb

## CSV 파일 분석 샘플 

BigQuery Cost Optimization.ipynb

## Vertex AI Evaluation 

genesis-g80-rag-evaluation-256.ipynb