cmake_minimum_required(VERSION 3.21)
project(EasyDB)

set(CMAKE_CXX_STANDARD 14)

add_executable(EasyDB main.cpp backend/tm/TransactionManager.h backend/tm/TransactionManager.cpp backend/common/AbstractCache.cpp backend/common/AbstractCache.h backend/dm/Page.cpp backend/dm/Page.h backend/dm/PageCache.cpp backend/dm/PageCache.h backend/dm/PageOne.cpp backend/dm/PageOne.h backend/dm/PageX.cpp backend/dm/PageX.h backend/dm/DataItem.cpp backend/dm/DataItem.h backend/dm/DataManager.cpp backend/dm/DataManager.h backend/dm/PageInfo.h backend/dm/PageIndex.h backend/dm/Logger.h backend/dm/Recover.h backend/dm/Recover.cpp backend/vm/Entry.h backend/vm/VersionManager.h backend/vm/Transaction.h backend/vm/VersionManager.cpp backend/vm/Visibility.h backend/vm/Visibility.cpp backend/vm/LockTable.h backend/im/Node.h backend/im/BPlusTree.h backend/tbm/Field.h backend/tbm/FieldCalRes.h backend/parser/SingleExpression.h backend/tbm/Table.h backend/tbm/TableManager.h backend/parser/Create.h backend/tbm/BeginRes.h)
