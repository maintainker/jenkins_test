# 단순 express jenkins test 용입니다.

```mermaid
  classDiagram
    User <|-- Apply
    Apply <|-- Attachment

    User: int id-pk
    User: varchar_30 user_id
    User: varchar_50 password
    User: varchar_30 nickname
    User: Date create_time
    User: Date updated_time
    User: Date|null deleted_time

    Apply: int id-pk
    Apply: varchar_30 company_name
    Apply: varchar_30 apply_method
    Apply: varchar_30 position
    Apply: varchar_30 apply_link
    Apply: varchar_30 apply_status
    Apply: varchar_100 memo

```
